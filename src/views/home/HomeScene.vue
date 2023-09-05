<template>
    <div class="sketch-container">
        <div id="three-sketch" ref="sketch"></div>
    </div>
</template>

<script setup lang="ts">
import { onBeforeMount, onMounted, ref, Ref } from "vue";
import SceneBuilder from "./SceneBuilder";

const sketch: Ref<HTMLElement | null> = ref(null);
const width: number = window.innerWidth;
const height: number = window.innerHeight;
let scene: SceneBuilder | null = null;

function updateWindowWidth() {
    if (scene instanceof SceneBuilder) {
        scene.camera.updateProjectionMatrix();
        scene.camera.aspect = window.innerWidth / window.innerHeight;
        updateWindowWidth();
    }
}

onMounted(() => {
    if (sketch.value) {
        scene = new SceneBuilder(sketch.value as HTMLElement, width, height);
        scene.render();
        window.addEventListener("resize", updateWindowWidth);
    }
});

onBeforeMount(() => {
    window.removeEventListener("resize", updateWindowWidth);
});
</script>

<style lang="scss">
@import "./HomeScene.scss";
</style>

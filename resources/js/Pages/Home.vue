<template>
    <div>My Name Is {{ name }}</div>
    <p>In this series we will use the followig thing</p>
    <ul>
        <li v-for="FrameWorks of FrameWork" v-text="FrameWorks"></li>
    </ul>
    <NavBar></NavBar>
</template>

<script setup>
import NavBar from "../Shared/NavBar.vue";
const props = defineProps({
    name: String,
    FrameWork: Array,
});
</script>

<style lang="scss" scoped></style>

<template>
    <canvas id="Lesson1" width="400" height="400" style="border:1px solid #d3d3d3;background: black;"></canvas>
</template>

<style lang="scss">
    @import './index.scss';
</style>

<script>
import { init } from "./index";

export default {
    name: 'Lesson2',
    data() {
        return {
            
        };
    },
    
    methods: {
        
    },
    mounted() {
        init();
    },
};
</script>

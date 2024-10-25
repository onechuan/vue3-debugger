<template>
    <div class="loading">
        {{ msg }}
    </div>
</template>

<script lang='ts' setup>

defineProps<{
    msg: string;
    duration: number;
}>()

</script>

<style scoped>
.loading{
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    z-index: 10;
    background-color: red;
    display: flex;
    width: 300px;
    height:300px;
}
</style>

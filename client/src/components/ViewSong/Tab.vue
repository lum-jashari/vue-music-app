<template>
    <panel title="Guitar Tab" class="ml-2 mt-2">
        <textarea name="rab" readonly v-model="song.tab"></textarea>
    </panel>
</template>

<script>
export default {
    props: ["song"],
};
</script>

<style scoped>
textarea {
    width: 100%;
    font-family: monospace;
    border: none;
    height: 600px;
    border-style: none;
    border-color: transparent;
    overflow: auto;
    padding: 40px;
}
</style>

<template>
    <button type="button" class="my-button">my button</button>
</template>

<script>
export default {
    name: 'my-button',
    created () {
        console.log('created my button');
    }
}
</script>

<style>
.my-button {color: red}
</style>
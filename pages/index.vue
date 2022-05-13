<template>
    <h1 class="text-3xl font-bold underline">
        Hello world!!
    </h1>
    <div>
        Counter: {{ counter }}
        <button class="bg-sky-500 hover:bg-sky-700 px-5 py-2 text-sm leading-5 rounded-full font-semibold text-white"
            @click="counter++">
            +1
        </button>

    </div>
</template>

<script setup>
const counter = useState('counter', () => 0);
</script>

<style scoped>
</style>
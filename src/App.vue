<script>
import MainTitle from './components/MainTitle.vue';

export default {
    components: {
        MainTitle
    },
    data() {
        return {
            count: 0,
        }
    }
}
</script>

<template>
    <MainTitle />

    <button @click="count++">Count is: {{ count }}</button>
</template>

<style scoped>
button {
  font-weight: bold;
  color: red;
}
</style>

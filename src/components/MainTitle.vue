<script>
export default {
    data() {
        return {
            message: 'Ciao Vite dal componente!'
        }
    }
}
</script>

<template>
    <h1>
        {{ message }}
    </h1>
</template>

<style scoped>
h1 {
    color: green;
}
</style>

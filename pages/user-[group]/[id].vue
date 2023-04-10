<template>
    <div>
        <h1>user page</h1>
        <NuxtLink to="/">Index</NuxtLink>
        <p>group: {{ $route.params.group }}</p>
        <p>id: {{ $route.params.id }}</p>
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>

</style>

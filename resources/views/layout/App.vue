<template>
    <div class="flex h-screen bg-grey-lightest flex-col md:flex-row font-light w-full">
        <div class="miku-blue-background w-screen md:w-64 md:min-w-64 overflow-hidden min-h-28"></div>

        <div class="flex-grow flex-shrink flex-auto overflow-y-scroll">
            <header class="h-24 px-8 bg-gray-700"></header>
        </div>
    </div>
</template>

<script>
export default {
    name: 'App',
}
</script>

<style>
.miku-blue-background {
    background: rgb(172,254,249);
    background: linear-gradient(0deg, rgba(172,254,249,1) 0%, rgba(77,186,226, 1) 100%);
}
</style>

<template>
    <h1>{{ title }}</h1>>
</template>

<script>
export default {
    name: 'to-do-list',
    props: {
        title: {
            type: String,
            required: false,
        }
    },

}
</script>

<style>

</style>
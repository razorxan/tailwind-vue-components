<template>
    <nav class="bg-teal-500">
        <ul class="flex">
            <slot></slot>
        </ul>
    </nav>
</template>

<script>
export default {
    name: "Navbar",
    props: {
        value: {
            type: Boolean,
            required: false,
            default: false
        }
    },
    methods: {
        toggle() {}
    }
};
</script>

<style>
</style>
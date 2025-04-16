<script setup>
    import { Head } from '@inertiajs/vue3';
</script>

<template>
    <Head :title="` | ${$page.component}`" />
    <div>
        <h1>{{$page.props.auth.user}}</h1>
    </div>
</template>

<style lang="scss" scoped></style>
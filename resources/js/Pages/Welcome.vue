<template>
    <Nav />

    <Head>
        <title>Welcome</title>
        <meta name="description" content="The welcome page.">
    </Head>
</template>

<script>
import Nav from "@/Shared/Nav.vue";
import { Head } from '@inertiajs/vue3';

export default {
    components: { Nav, Head }
};
</script>

<template>
    <nav>
        <ul class="flex justify-center space-x-48 pt-6 pb-6">
            <li>
                <Link href="/">
                    <a class="group relative inline-block text-sm font-medium text-indigo-600 focus:outline-none focus:ring active:text-indigo-500">
                    <span class="absolute inset-0 translate-x-0.5 translate-y-0.5 bg-indigo-600 transition-transform group-hover:translate-y-0 group-hover:translate-x-0"></span>
                    <span class="relative block border border-current bg-white px-8 py-3">Home /></span></a>
                </Link>
            </li>
            <li>
                <Link href="/Projects">
                    <a class="group relative inline-block text-sm font-medium text-indigo-600 focus:outline-none focus:ring active:text-indigo-500">
                    <span class="absolute inset-0 translate-x-0.5 translate-y-0.5 bg-indigo-600 transition-transform group-hover:translate-y-0 group-hover:translate-x-0"></span>
                    <span class="relative block border border-current bg-white px-8 py-3">Projects /></span></a>
                </Link>
            </li>
            <li>
                <Link href="/About">
                    <a class="group relative inline-block text-sm font-medium text-indigo-600 focus:outline-none focus:ring active:text-indigo-500">
                    <span class="absolute inset-0 translate-x-0.5 translate-y-0.5 bg-indigo-600 transition-transform group-hover:translate-y-0 group-hover:translate-x-0"></span>
                    <span class="relative block border border-current bg-white px-8 py-3">About /></span></a>
                </Link>
            </li>
            <li>
                <Link href="/Contact">
                    <a class="group relative inline-block text-sm font-medium text-indigo-600 focus:outline-none focus:ring active:text-indigo-500">
                        <span class="absolute inset-0 translate-x-0.5 translate-y-0.5 bg-indigo-600 transition-transform group-hover:translate-y-0 group-hover:translate-x-0"></span>
                        <span class="relative block border border-current bg-white px-8 py-3">Contact /></span></a>
                </Link>
            </li>
        </ul>
    </nav>
</template>

<script>
import { Link } from "@inertiajs/vue3";

export default {
    components: { Link }
};
</script>

<!--
    HyperUI: https://www.hyperui.dev/
        - Buttons
-->

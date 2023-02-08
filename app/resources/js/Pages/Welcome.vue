<script setup>
import { Head, Link } from '@inertiajs/vue3';

defineProps({
    
});
</script>

<template>
    <Head title="Welcome" />

    <!-- <Link
        v-if="$page.props.auth.user"
        :href="route('dashboard')"
        class="text-sm text-gray-700 dark:text-gray-500 underline"
    >
        Dashboard
    </Link> -->

    <Link :href="route('login')">Login</Link>

    
</template>

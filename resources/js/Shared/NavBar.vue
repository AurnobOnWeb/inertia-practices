<template>
    <nav>
        <ul>
            <li><Link href="/">Home</Link></li>
            <li><Link href="/users">User</Link></li>
            <li><Link href="/settings">Setting</Link></li>
            <li><Link href="/logout">logout</Link></li>
        </ul>
    </nav>
</template>

<script setup>
import { Link } from "@inertiajs/vue3";
</script>

<style lang="scss" scoped></style>

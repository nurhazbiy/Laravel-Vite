<script setup>
import {Link} from '@inertiajs/vue3'
</script>

<template>
    <main>
        <article>
            <slot/>
        </article>
        <footer class="flex justify-center">
            <div >
                <Link href="/">Dashboard</Link>
                |
                <Link href="/user">User</Link>
            </div>
        </footer>
    </main>
</template>

<template>
    <div class="grid min-h-screen grid-cols-1 md:grid-cols-6 funnel-display">
        <aside class="bg-gray-900 col-span-1 px-4 pt-20 text-white">
            <SidebarNav />
        </aside>
        <main class="col-span-5 px-4 pt-20">
            <div id="about-the-game">
                <h3 class="text-xl my-5">Funny Games for Kids (iOS)</h3>
                <p>The application does not collect any user data.</p>
                <p>In case this changes in future, always check this page for updates</p>
            </div>
        </main>
    </div>
</template>
<script lang="ts" setup>
import SidebarNav from '~/components/sidebar/nav.vue'

useHead({
    link: [
        {
            rel: 'preconnect',
            href: 'https://fonts.googleapis.com'
        },
        {
            rel: 'preconnect',
            href: 'https://fonts.gstatic.com',
            crossorigin: ""
        },
        {
            rel: "stylesheet",
            href: "https://fonts.googleapis.com/css2?family=Funnel+Display:wght@300..800&display=swap"
        }
    ]
})
</script>
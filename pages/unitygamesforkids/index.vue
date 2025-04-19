<template>
    <div class="grid min-h-screen grid-cols-1 md:grid-cols-6 funnel-display">
        <aside class="bg-gray-900 col-span-1 px-4 pt-20 text-white">
            <p class="text-md">Support</p>
            <h1 class="text-3xl">Funny Games For Kids</h1>
            <div class="mb-20" />
            <nav class="flex flex-col">
                <NuxtLink to="/unitygamesforkids#about-the-game">About the Game</NuxtLink>
                <NuxtLink to="/unitygamesforkids#contacts">Contacts</NuxtLink>
            </nav>
        </aside>
        <main class="col-span-5 px-4 pt-20">
            <div id="about-the-game">
                <h3 class="text-xl my-5">Funny Games for Kids (iOS)</h3>
                <p>Funny Games for Kids (iOS) is made as a personal side project, with the sole purpose to learn how to develop games using Unity</p>
                <p>The application itself is made to host unlimited number of (Unity) Scenes, each providing a unique experience</p>
                <h3 class="text-xl my-5">BalloonPopper</h3>
                <p>This games is made to run on any pointer devices ( built-in Unity support for touch, mouse and pens )</p>
                <p>The game consists of</p>
                <ul class="list-disc pl-10 pt-5 pb-2">
                    <li>Number of balloons - 2.</li>
                    <li>Each time the player clicks on the ballon, it randomizes the positiona and the color of the balloon.</li>
                    <li>Each time a balloon is clicked, it increases the user score.</li>
                    <li>Each succesful click gradually increases the speed of the balloons. Once the users click 30 times, max balloon speed is reached.</li>
                    <li>The User is allowed to click as many times, without a time or a count limit.</li>
                </ul>
            </div>

            <div id="contacts">
                <h3 class="text-xl my-5">Contacts</h3>
                <p>Use our <NuxtLink to="https://github.com/dimitarsi/ios-apps-support-pages/issues" class="underline">github repository</NuxtLink> to submit an issue or ask question.</p>
            </div>
        </main>
    </div>
</template>
<script lang="ts" setup>
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
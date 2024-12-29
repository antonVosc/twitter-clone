<template>
    <div class="flex flex-col h-screen">
        <div class="p-2 my-2 rounded-full hover:bg-blue-50 w-min dark:hover:bg-white/20" :class="transition">
            <nuxt-link to="/">
                <div class="w-8 h-8">
                    <LogoTwitter />
                </div>
            </nuxt-link>
        </div>
    </div>
</template>

<script setup>
    const transition = 'transition ease-in-out duration-350'
</script>
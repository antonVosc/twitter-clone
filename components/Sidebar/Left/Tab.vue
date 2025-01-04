<template>
    <nuxt-link to="#" class="flex items-center p-3 w-min hover:bg-gray-200" :class="defaultTransition">
        <div class="w-6 h-6 text-dark">
            <slot name="icon"></slot>
        </div>

        <div>
            <slot name="name"></slot>
        </div>
    </nuxt-link>
</template>

<script setup>
    const { defaultTransition } = useTailwindConfig()
</script>
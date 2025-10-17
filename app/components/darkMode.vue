<script setup lang="ts">
import { Icon } from '@iconify/vue'
const colorMode = useColorMode();
</script>

<template>
    <di class="flex gap-4">
        <div @click="colorMode.preference = 'dark'">
            <Icon icon="radix-icons:moon"
                class="h-[1.2rem] w-[1.2rem] rotate-0 scale-100 transition-all dark:-rotate-90 dark:scale-0" />
        </div>
        <div @click="colorMode.preference = 'light'">
            <Icon icon="radix-icons:sun"
                class="h-[1.2rem] w-[1.2rem] rotate-0 scale-100 transition-all dark:-rotate-90 dark:scale-0" />
        </div>
    </di>
</template>
<script setup lang="ts">
import { Input } from '@/components/ui/input';
</script>

<template>

    <div class="h-dvh min-w-dvw flex flex-col items-center justify-center">
        <div>
            <DarkMode class="m-auto" />
        </div>
        <div class="grid w-full max-w-sm gap-1.5">
            <Label for="email">Email</Label>
            <Input id="email" type="email" placeholder="Email" />
            <Label for="email">Password</Label>
            <Input id="email" type="password" placeholder="Email" />
        </div>
    </div>
</template>
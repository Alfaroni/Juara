<script setup>
    import SwitchTheme from './SwitchTheme.vue';
</script>

<template>
    <header class="fixed top-0 inset-x-0 z-20 bg-white/20 backdrop-blur-lg dark:bg-neutral-900/20">
        <div class="container max-w-5xl px-4">
            <div class="flex items-center min-h-16 justify-between">
                <div class="flex-1">
                    <a href=""><img src="../assets/images/juara1.png" alt="logo" width="144" height="36" class="object-contain h-12 object-left"></a>
                </div>
                <div><SwitchTheme /></div>
            </div>
        </div>
    </header>
</template>
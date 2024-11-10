<template>
    <div class="flex px-2 py-3 items-center bg-[peru]">
        <h1 class="text-white">Sandbox</h1>
        <nav class="ml-auto">
            <NuxtLink class="flex gap-2 items-center justify-center p-2 rounded border-2 hover:bg-white font-mono"
                to="https://github.com/vr1eva/sandbox" target="_blank">
                <nuxt-icon width="16" height="16" name="github" prefilled />
                <span>View source code on GitHub</span>
            </NuxtLink>
        </nav>
    </div>
</template>
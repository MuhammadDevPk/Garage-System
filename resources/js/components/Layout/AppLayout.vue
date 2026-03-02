<script setup lang="ts"></script>

<template>
    <div class="flex h-screen bg-gray-100">
        <sidebar />

        <div class="flex flex-1 flex-col">
            <Topbar />
            <main class="p-6 overflow-y-auto">
                <slot />
            </main>
        </div>
    </div>
</template>
<script setup>
import { Link } from '@inertiajs/vue3';
</script>

<template>
    <!-- Left Sidebar -->
    <aside class="w-64 bg-white px-5 py-8 flex flex-col h-screen overflow-y-auto shrink-0 border-r border-gray-100">
        <!-- Logo -->
        <div class="mb-10 px-2">
            <div class="text-xl font-bold italic flex items-center mb-2">
                <div class="bg-gray-800 text-green-400 px-3 py-1 font-black">Karr</div>
                <div class="bg-green-500 text-white px-3 py-1 font-black">Kraft</div>
            </div>
        </div>

        <!-- Navigation -->
        <nav class="flex-1 space-y-3">
            <Link href="/"
                class="flex items-center gap-4 text-gray-500 hover:bg-gray-50 px-4 py-3 rounded-xl font-medium transition-colors border border-transparent hover:border-gray-100">
                <!-- Dashboard Icon -->
                <svg class="w-5 h-5 text-green-500" fill="currentColor" viewBox="0 0 20 20">
                    <path
                        d="M5 3a2 2 0 00-2 2v2a2 2 0 002 2h2a2 2 0 002-2V5a2 2 0 00-2-2H5zm0 8a2 2 0 00-2 2v2a2 2 0 002 2h2a2 2 0 002-2v-2a2 2 0 00-2-2H5zm6-8a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2V5zm0 8a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2v-2z">
                    </path>
                </svg>
                Dashboard
            </Link>
            <Link href="/inventory"
                class="flex items-center gap-4 text-gray-500 hover:bg-gray-50 px-4 py-3 rounded-xl font-medium transition-colors border border-transparent hover:border-gray-100">
                <!-- Inventory Icon -->
                <svg class="w-5 h-5 text-green-500" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                        d="M20 7l-8-4-8 4m16 0l-8 4m8-4v10l-8 4m0-10L4 7m8 4v10M4 7v10l8 4"></path>
                </svg>
                Inventory
            </Link>
            <Link href="/repair-tracker"
                class="flex items-center gap-4 text-gray-500 hover:bg-gray-50 px-4 py-3 rounded-xl font-medium transition-colors border border-transparent hover:border-gray-100">
                <!-- Repair Tracker Icon -->
                <svg class="w-5 h-5 text-green-500" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                        d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z">
                    </path>
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                        d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"></path>
                </svg>
                Repair tracker
            </Link>
            <Link href="/customers"
                class="flex items-center gap-4 text-gray-500 hover:bg-gray-50 px-4 py-3 rounded-xl font-medium transition-colors border border-transparent hover:border-gray-100">
                <!-- Customers Icon -->
                <svg class="w-5 h-5 text-green-500" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                        d="M12 4.354a4 4 0 110 5.292M15 21H3v-1a6 6 0 0112 0v1zm0 0h6v-1a6 6 0 00-9-5.197M13 7a4 4 0 11-8 0 4 4 0 018 0z">
                    </path>
                </svg>
                Customers
            </Link>
            <!-- Active Appointments Menu Item -->
            <Link href="/appointments"
                class="flex items-center gap-4 bg-green-500 text-white px-4 py-3 rounded-xl font-semibold shadow-lg shadow-green-500/30">
                <!-- Appointments Icon -->
                <svg class="w-5 h-5 opacity-90 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                        d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z">
                    </path>
                </svg>
                Appointments
            </Link>
            <Link href="/staff-management"
                class="flex items-center gap-4 text-gray-500 hover:bg-gray-50 px-4 py-3 rounded-xl font-medium transition-colors border border-transparent hover:border-gray-100">
                <!-- Staff Management Icon -->
                <svg class="w-5 h-5 text-green-500" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                        d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z">
                    </path>
                </svg>
                Staff Management
            </Link>
        </nav>
    </aside>
</template>
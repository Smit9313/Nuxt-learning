<template>
    <nav class="bg-white shadow-md sticky top-0 right-0">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16 items-center">
                <div class="flex">
                    <div class="flex-shrink-0 flex items-center">
                        <NuxtLink to="/" class="text-gray-900 font-bold text-xl">Your Brand</NuxtLink>
                    </div>
                </div>
                <div class="flex justify-center flex-grow">
                    <div class="hidden sm:ml-6 sm:flex sm:space-x-8">
                        <NuxtLink to="/"
                            class="border-indigo-500 text-gray-900 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium"
                            aria-current="page">Home</NuxtLink>
                        <NuxtLink to="/services"
                            class="border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">
                            Services</NuxtLink>
                        <NuxtLink to="/about"
                            class="border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">
                            About</NuxtLink>
                        <NuxtLink to="/contact"
                            class="border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">
                            Contact</NuxtLink>
                    </div>
                </div>
                <div class="flex items-center">
                    <!-- <NuxtLink to="/login"
                        class="text-gray-600 hover:text-gray-900 px-3 py-2 rounded-md text-sm font-medium">Sign In
                </NuxtLink>
                <NuxtLink to="/register" class="bg-indigo-600 text-white px-3 py-2 rounded-md text-sm font-medium ml-4">
                    Sign Up</NuxtLink> -->
            </div>
        </div>
    </div>
</nav></template>
  
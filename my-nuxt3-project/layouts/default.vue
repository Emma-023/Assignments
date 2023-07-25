<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="container mx-auto p-4 flex justify-between">
                <NuxtLink to="/" class="font-bold">Assignment</NuxtLink>
                <ul class="flex gap-4">
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/Hwasa" class="btn">Hwasa</NuxtLink></li>
                    <li><NuxtLink to="/Solar" class="btn">Solar</NuxtLink></li>
                    <li><NuxtLink to="/Wheein" class="btn">Wheein</NuxtLink></li>
                    <li><NuxtLink to="/Moonbyul" class="btn">Moonbyul</NuxtLink></li>
                </ul>
            </nav>
        </header>

        <!-- page content go here -->
        <div class="container mx-auto p-4">
            <slot />
        </div>
    </div>
</template>

<style scoped>
    .router-link-exact-active {
        color: #12b488;
    }
</style>
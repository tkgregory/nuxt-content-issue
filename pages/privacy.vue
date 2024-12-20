<template>
    <main>
        <h1 class="text-3xl font-bold mb-8">Privacy</h1>

        <div>
            <NuxtLink to="/support">Support</NuxtLink> &nbsp;
            <NuxtLink to="/privacy">Privacy</NuxtLink>
        </div>

        <ContentDoc path="/privacy" :head="false" />

    </main>
</template>
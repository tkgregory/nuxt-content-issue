<template>
    <main>
        <h1 class="text-3xl font-bold mb-8">Support</h1>

        <div>
            <NuxtLink to="/support" class="link link-hover">Support</NuxtLink> &nbsp;
            <NuxtLink to="/privacy" class="link link-hover">Privacy</NuxtLink>
        </div>

        <ContentDoc path="/support" :head="false" />

    </main>
</template>
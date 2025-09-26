<script lang="ts" setup>
import Header from "../Components/Header.vue"
import Footer from "../Components/Footer.vue"
</script>

<template>
    <div>
        <Header />
        <slot />
        <Footer/>
    </div>
</template>

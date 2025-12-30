<template>
    <div>

        <!-- Se utiliza para que se le de preferencia a la carpeta Blog, pero todo lo de antes se mostrará de todas maneras (el header) -->
        <NuxtPage/>
    </div>
</template>

<script setup>
    // sirve para tomar todo lo que se encuentra en el layout de blog
    definePageMeta({
        layout: 'blog-layout',
    })

</script>

<style  scoped>

</style>

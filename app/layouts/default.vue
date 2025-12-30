<template>
    <div>
        <!-- Para utilizar un layout por defecto, se le llama default al archivo  -->
        <!-- to sirve para hacer el enrutamiento de la pagina (hacer link a la etiqueta)-->
        <NuxtLink to="/"> Home </NuxtLink>
        <nuxt-link to="/about"> ABOUT </nuxt-link>
        <nuxt-link to="/products"> PRODUCTS </nuxt-link>
        <nuxt-link to="/login"> LOGIN </nuxt-link>
        <nuxt-link to="/register"> REGISTER </nuxt-link>
        
        <!-- Contenido dinámico de las páginas -->
        <slot/>

        <footer>

            <p>2025 My Nuxt page App</p>
        </footer>
    </div>
</template>

<script setup>

</script>

<style scoped>

</style>
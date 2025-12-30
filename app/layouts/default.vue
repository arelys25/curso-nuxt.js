<template>
    <div>
        <!-- Para utilizar un layout por defecto, se le llama default al archivo  -->
        
        <!-- Mandar a llamar un componente -->

        <AppHeader/>

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
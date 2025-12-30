<template>
    <div>
        <!-- to sirve para hacer el enrutamiento de la pagina (hacer link a la etiqueta)-->
        
        <nuxt-link to="/login"> LOGIN </nuxt-link>
        <nuxt-link to="/register"> REGISTER </nuxt-link>

        <slot></slot>

        <footer>
            <p>Auth Layout</p>
        </footer>
    
    </div>
</template>

<script setup>
    

</script>

<style scoped>

</style>

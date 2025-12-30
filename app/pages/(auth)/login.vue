<template>
    <div>

        <!-- Aquí podemos organizar las rutas con la carpeta. Solo la omitimos y escribimos en el navegador directamente /login -->

        <h1>Login Page</h1>
    </div>
</template>

<script setup>

    // funcion que sirve para que la pagina detecte que hya un layout especifico 

    definePageMeta({
        layout: 'auth-layout',
    });

</script>

<style scoped>

</style>
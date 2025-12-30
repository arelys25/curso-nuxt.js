<template>
    <div>
        <!-- Los slugs pueden ser dinamicos, como un id o un nombre, o simplemente el nombre slug -->
        <h1>Producto 1</h1>

        <!-- parametros de ruta. Se imprimirá lo que se le ponga en la url después de products/... en este caso llamamos slug a la variable dinámica del archivo -->
        <h2>{{ $route.params.slug }}</h2>
    </div>
</template>

<script setup>

    // otra forma de acceder a los parámetros de ruta
    const route = useRoute()

    console.log(route.params.slug)

</script>

<style scoped>

</style>
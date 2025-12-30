<template>
  <div>
    <!-- <NuxtRouteAnnouncer />
    <NuxtWelcome /> -->

    <!-- to sirve para hacer el enrutamiento de la pagina (hacer link a la etiqueta)-->
    <NuxtLink to="/"> Home </NuxtLink>
    <nuxt-link to="/about"> ABOUT </nuxt-link>
    <nuxt-link to="/products"> PRODUCTS </nuxt-link>
    <nuxt-link to="/login"> LOGIN </nuxt-link>
    <nuxt-link to="/register"> REGISTER </nuxt-link>
    
    <NuxtPage/>
  </div>
</template>

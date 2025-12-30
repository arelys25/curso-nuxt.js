<template>
    <div>
        <h1 class="h1">{{ title }}</h1>
    </div>
</template>

<script setup lang="ts">

    // es como hacerle un constructor a la etiqueta de TitlePage
    interface Props {
        title: string,
    };

    const {title} = defineProps<Props>();

</script>

<style  scoped>
    .h1 {
        color: brown;
        font-size: 45px;
    }
</style>
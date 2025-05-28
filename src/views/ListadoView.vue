<script setup>
import Titulo from '../components/TituloVue.vue'
import Template from '../components/Template.vue'
</script>
<template>
  <titulo texto="Hola soy un titulo" />
  <Template>
    <template #parrafo>
      <p class="animate__animated animate__lightSpeedInRight">Esto se muestra solo en parrafo</p>
    </template>
    <p>Todo lo que este dentro va a slot</p>
  </Template>
</template>

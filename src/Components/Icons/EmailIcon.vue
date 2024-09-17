<script setup>
import { ref } from 'vue';

const message = ref(null)
const clipboard = () => {
  navigator.clipboard.writeText('ibarra.h.leonel@gmail.com')
    .then(() => {
      message.value.classList.toggle('d-none')
      setTimeout(() => {
        message.value.classList.toggle('d-none')
      }, 1500)
    })
}
</script>
<template>
  <button type="button" title="Copiar" @click="clipboard" class="position-relative">
    <i class="fa-solid fa-envelope"></i>
    <span class="position-absolute top-0 start-100 translate-middle badge rounded-pill bg-success d-none" ref="message">
      copiado!
    </span>
  </button>
</template>

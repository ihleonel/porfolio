<script setup>
import LinkedinIcon from './Icons/LinkedinIcon.vue'
import GithubIcon from './Icons/GithubIcon.vue'
import TwitterIcon from './Icons/TwitterIcon.vue';

const clipboard = () => {
  navigator.clipboard.writeText('ibarra.h.leonel@gmail.com')
}

</script>
<template>
  <div class="wrapper">
    <div class="social-media">
      <LinkedinIcon />
    </div>
    <div class="social-media">
      <GithubIcon />
    </div>
    <div class="social-media">
      <TwitterIcon />
    </div>
    <div class="email">
      ibarra.h.leonel@gmail.com

      <button class="copy" title="Copiar" @click="clipboard">
        <i class="fa-solid fa-copy"></i>
      </button>
    </div>
  </div>
</template>
<style scoped>
.wrapper {
  display: flex;
  justify-content: end;
}
.email {
  width: 300px;
  padding: .5em;
  border: 2px solid var(--secondary-color);
  border-radius: 10px;
  color: var(--secondary-color);

  .copy {
    margin-left: 17px;
    background-color: transparent;
    color: var(--secondary-color);
    border: 0;
  }
}
</style>

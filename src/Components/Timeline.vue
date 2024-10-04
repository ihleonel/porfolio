<script setup>
</script>
<template>
  <!-- Section: Timeline -->
<div class="mt-3">
  <ul class="timeline">
    <li class="timeline-item">
      <h5 class="fw-bold title">Outsource Argentina</h5>
      <p class="mb-2 dates">Abril 2023 - Actualidad</p>
      <p class="mb-5">
        Desarrollo de sistemas para el ambito privado.
        En los proyectos en los que participé se utilizaron: Git, Gitlab, PHP, Laravel,
        Docker, Vue, Bootstrap, Wordpress, CakePHP, Nginx y Apache2. Scrumban como
        metodología en Jira. Configuración para CI/CD con Deployer. Configuración
        de servidores para el despliegue de sistemas webs. Integración con SignNow para
        la administración de firma electrónica de documentos.
      </p>
    </li>
    <li class="timeline-item">
      <h5 class="fw-bold title">ECI Solution Software</h5>
      <p class="mb-2 dates">Abril 2022 - Abril 2023</p>
      <p class="mb-5 description">
        Desarrollo de sistemas para el ambito privado. Modernización de aplicaciones existentes.
        En el proyecto en el que participé se utilizaron: Git, Bitbucket, PHP, Laravel,
        Docker, Bootstrap, Reactjs. Scrumban como metodología con Jira. Integración con
        QuickBooks para la administración de facturas.
      </p>
    </li>
    <li class="timeline-item">
      <h5 class="fw-bold title">Gobierno de la provincia de Salta</h5>
      <p class="mb-2 dates">Abril 2018 - Abril 2022</p>
      <p class="mb-5">
        Desarrollo de sistemas para el ambito público, enfocados en la gestion de documentos y modernización del estado.
        Firma digital de documentos. En los proyectos en los que participé se utilizaron: Git,
        Gitlab, PHP, Laravel, Docker, Elastic, Vue, Bootstrap, React Native, Expo. Scrumban
        como metodología. Configuración para CI/CD.
      </p>
    </li>
  </ul>
</div>
<!-- Section: Timeline -->
</template>
<style scoped>
.timeline {
  margin: 0;
  border-left: 1px solid var(--main-color);
  position: relative;
  list-style: none;
}

.timeline .timeline-item {
  position: relative;
}

.timeline .timeline-item:after {
  position: absolute;
  display: block;
  top: 0;
}

.timeline .timeline-item:after {
  background-color: var(--main-color);
  top: 4px;
  left: -40px;
  border-radius: 50%;
  height: 15px;
  width: 15px;
  content: "";
}

.dates {
  color: var(--secondary-color);
}
</style>

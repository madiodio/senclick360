<template>
  <section class="container">
    <div>
      <logo/>
      <h1 class="title">
        SenClick 360
      </h1>
      <h2 class="subtitle">
        Agence de communication digitale
      </h2>
      <h3 class="sub-subtitle">
        Coming Soon!
      </h3>
      <div class="links">
        <a href="http://madiodio.blogspot.sn/" target="_blank" class="button--green">Aller sur le blog</a>
        <a href="mailto:papigaye1@gmail.com" target="_blank" class="button--grey">Contactez-nous</a>
      </div>
    </div>
  </section>
</template>

<script>
import Logo from "~/components/Logo.vue";

export default {
  components: {
    Logo
  }
};
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  display: block;
  font-weight: 600;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.sub-subtitle {
  font-weight: 300;
  font-size: 14px;
  color: #526488;
  text-transform: uppercase;
  letter-spacing: 14px;
  padding-bottom: 10px;
}

.links {
  padding-top: 15px;
}
</style>

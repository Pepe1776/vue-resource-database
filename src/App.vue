<template>
  <the-header title="Resource Database"></the-header>
  <the-resources></the-resources>
</template>

<script>
import TheHeader from './components/layouts/TheHeader.vue';
import TheResources from './components/learning-resources/TheResources.vue';

export default {
  components: {
    TheHeader,
    TheResources,
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

@font-face {
  font-family: 'Exo';
  src: url('../public/Exo2-Italic-VariableFont_wght.ttf') format('truetype');
}

* {
  box-sizing: border-box;
  font-family: 'Exo';
}

body {
  margin: 0;
}
</style>

<template>
  <button :class="mode">
    <slot></slot>
  </button>
</template>

<script>
export default {
  props: ['mode'],
};
</script>

<style scoped>
button {
  padding: 0.75rem 1.5rem;
  font-family: inherit;
  background-color: #007eaf;
  border: 1px solid #025272;
  color: white;
  cursor: pointer;
}

button:hover,
button:active {
  background-color: #025272;
  border-color: #270041;
}

.flat {
  background-color: transparent;
  color: #0a0061;
  border-color: #270041;
}

.flat:hover,
.flat:active {
  background-color: #00fddb;
  border-color: #270041;
}
</style>

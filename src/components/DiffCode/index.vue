<script setup>
import { ref } from 'vue';
import { STUDENTS } from './const';

const code = ref(STUDENTS[0]);

// function increment() {
//   count.value++
// }
  // defineProps({
  //   msg: {
  //     type: String,
  //     required: true
  //   }
  // })
</script>

<template>
  <div class="container">
    <pre>
      <code>{{ code }}</code>
    </pre>
  </div>
</template>

<style scoped>

.container {
  background-color: azure;
  color: black;
  /* box-shadow: ; */
}
/* h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
} */

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>

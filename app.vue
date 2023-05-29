<template>
  <main>
  <div>
    <h1>Hello World!!</h1>
  </div>
  <button @click="clickBottom">click</button>
  <h2>{{ a1 }}</h2>
<div class="btn btn-success"> btn-success</div>
  </main>
</template>

<script setup lang="ts">
  import { ref } from "vue";
  const  a1 = ref(0) ;

  const clickBottom = () => {
    a1.value +=1;
  };

</script>

<style>
h1{
color: brown;
}


</style>
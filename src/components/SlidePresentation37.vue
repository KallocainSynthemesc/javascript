<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Opérateurs arithmétiques</div>
    <div class="content">
      <p>Calcule le temps</p>
      <MonacoEditor
        code='var hours = 40;
var clock = 12;
var time;
//mettre le calcul ici
console.log("it is "+time+" o&apos;clock");'
      />
    </div>
  </div>
</template>

<style scoped></style>

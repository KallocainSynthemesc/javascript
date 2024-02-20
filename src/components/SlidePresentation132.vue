<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Clean Code - Noms de variables</div>
    <div class="content">
      <p>Pouvez-vous donner de meilleurs noms à ces variables ?</p>
      <MonacoEditor
        code='//pouvez-vous changer les noms des variables pour que ce que fait mon code soit plus clair ?
let p = "Kilian";
let n = "Schropp";
let f = p + " " + n;
console.log("Mon nom complet est " + f);'
        editorIndex="35"
      />
    </div>
  </div>
</template>

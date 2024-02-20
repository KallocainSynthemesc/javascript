<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">if Tests - Exercice</div>
    <div class="content">
      <p>
        Faites un message d'accueil "bonne journée" si l'heure est inférieure à
        18:00
      </p>
      <MonacoEditor
        code='let hour = 16;
let greeting;
if () {
  greeting = "bonne journ&eacute;e";
} 

console.log(greeting);'
        editorIndex="9"
      />
    </div>
  </div>
</template>

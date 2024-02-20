<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">while Loops</div>
    <div class="content">
      <p>
        Le code suivant compte à partir de la valeur de a jusqu'à, mais sans
        inclure, b. Nous verrons plus tard une façon plus simple de le faire
        avec une boucle for
      </p>
      <MonacoEditor
        code="let a=0;
let b=10;

while (a &lt; b){ // Une fa&ccedil;on de coder les boucles de compteur
  console.log(a)
  a += 1 // Ou, a = a + 1
}"
        editorIndex="17"
      />
    </div>
  </div>
</template>

<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Clean Code - Noms de variables</div>
    <div class="content">
      <p>
        Je veux calculer l'aire du cercle, mais j'ai l'impression que mon code
        n'est pas très clair. Pouvez-vous le modifier ?
      </p>
      <MonacoEditor
        code='let r = 5
let a = 3.1415926535 * r * r;
console.log("L&apos;aire du cercle est " + a);'
        editorIndex="37"
      />
    </div>
  </div>
</template>

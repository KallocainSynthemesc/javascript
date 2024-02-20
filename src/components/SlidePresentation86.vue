<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">if Tests - Exercice</div>
    <div class="content">
      <p>
        Maintenant, nous prolongeons l'exercice précédent et souhaitons "Bonne
        soirée" après 18:00.
      </p>
      <MonacoEditor
        code='let hour = 18;
let greeting;
if (hour &lt; 18) {
  greeting = "bonne journ&eacute;e";
}

console.log(greeting);'
        editorIndex="10"
      />
    </div>
  </div>
</template>

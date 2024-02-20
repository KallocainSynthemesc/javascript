<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">if Tests - Exercice</div>
    <div class="content">
      <p>
        Ok maintenant, la dernière étape est de souhaiter une "bonne matinée"
        avant 9:00.
      </p>
      <MonacoEditor
        code='let hour = 18;
let greeting;
if (hour &lt; 18) {
  greeting = "bonne journ&eacute;e";
}

console.log(greeting);'
        editorIndex="11"
      />
    </div>
  </div>
</template>

<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Array.forEach() Loops</div>
    <div class="content">
      <p>
        La méthode forEach() appelle une fonction une fois pour chaque élément
        du tableau.
      </p>
      <MonacoEditor
        code='const numbers = [45, 4, 9, 16, 25];

numbers.forEach(myFunction);

function myFunction(value, index, array) {
  console.log("value:" + value + ", index:" + index);
}
'
        editorIndex="20"
      />
    </div>
  </div>
</template>

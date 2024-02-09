<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Function - Exercise</div>
    <div class="content">
      <p>
        Écrivez une fonction JavaScript pour imprimer le message "Hello World".
      </p>
      <MonacoEditor
        code='//&Eacute;crivez une fonction JavaScript pour imprimer le message "Hello World".
function displayMessage() {
  //mettre le code ici
}

displayMessage(); //"Hello World"'
      />
    </div>
  </div>
</template>

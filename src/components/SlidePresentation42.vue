<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Data Types - Strings</div>
    <div class="content">
      <p>Échapper la chaîne de caractères</p>
      <MonacoEditor
        code="//jette actuellement une erreur 
//parce qu'il n'est pas &eacute;chapp&eacute; correctement.
//Vous devez le faire. Corrige le bug, champion !
var text = &quot;&quot;j'adore&quot; tellement Perl que je n'arrive pas &agrave; y croire! Le meilleur langage de programmation au monde, je vous le jure ;)\&quot;;
console.log(text);"
        editorIndex="3"
      />
    </div>
  </div>
</template>

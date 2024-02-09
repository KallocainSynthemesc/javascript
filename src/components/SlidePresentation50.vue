<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Arrays</div>
    <div class="content">
      <p>
        Exercice : enregistrez 5 variables prédéfinies dans un tableau et donnez
        le contenu du tableau. Pour imprimer le contenu du tableau, utilisez
        <b>console.log</b> et concaténer les éléments du tableau avec le symbole
        <b>+</b>.
      </p>
      <MonacoEditor
        code='var hello = "Hello ";
var folks = "folks, ";
var now = "now ";
var you = "you ";
var know = "know";
var arrayExample = [] //le tableau cr&eacute;&eacute; ici, si vous voulez vous pouvez ajouter les &eacute;l&eacute;ments ici directement
var fullString; //concat&eacute;ner les &eacute;l&eacute;ments du tableau ici
console.log("The array contains now " 
              + arrayExample.length //donne la taille du tableau
              + " elements and results in the following string when concatinated: " 
              + fullString);'
      />
    </div>
  </div>
</template>

<style scoped></style>

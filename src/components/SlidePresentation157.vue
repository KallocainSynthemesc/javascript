<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Strings revisités - length</div>
    <div class="content">
      <p>
        J'ai un tableau de plusieurs longs mots français. Je veux trouver le mot
        le plus long dans mon tableau en utilisant l'attribut length.
      </p>
      <MonacoEditor
        code='let mots = ["dichlorodiph&eacute;nyltrichloro&eacute;thane", "hexakosioihexekontahexaphobie" , "d&eacute;sinstitutionnalisation"];

function trouverMotPlusLong(mots){
  let motPlusLong = "";
  return motPlusLong;
}

console.log(trouverMotPlusLong(mots));'
        editorIndex="42"
      />
    </div>
  </div>
</template>

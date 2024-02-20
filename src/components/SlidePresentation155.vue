<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Strings revisités - includes()</div>
    <div class="content">
      <p>
        Je veux compter toutes les occurrences de "eau" dans ma liste de mots.
        Pouvez-vous finir ma fonction en utilisant la méthode includes() de
        String?
      </p>
      <MonacoEditor
        code='let mots = ["beau", "voiture", "abre", "cadeau", "formation", "beaucoup", "chapeau"]
let lettres = "eau";

function compterToutesLesOccurrences(mots, lettres){
  let compteur = 0;
  return compteur;
}


const result = compterToutesLesOccurrences();
console.log(result);'
        editorIndex="41"
      />
    </div>
  </div>
</template>

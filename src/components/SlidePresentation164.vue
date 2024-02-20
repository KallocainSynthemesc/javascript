<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Array revisités - push()</div>
    <div class="content">
      <p>
        J'ai une liste de noms. Je veux créer une nouvelle liste avec les noms
        de la première liste qui commencent par la lettre "a". Utilisez les
        méthodes
        <a
          href="https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Global_Objects/String/startsWith"
          >startsWith()</a
        >
        ou l'index d'une chaîne de caractères et la méthode push() du tableau.
      </p>
      <MonacoEditor
        code='const noms = ["Anja", "anis","Magdalena","Barbara", "Anna", "Maria", "Veronika", "alexander", "Monika"];
const nomsCommen&ccedil;antParA = [];
for(let nom of noms){

}
console.log(nomsCommen&ccedil;antParA);
'
        editorIndex="44"
      />
    </div>
  </div>
</template>

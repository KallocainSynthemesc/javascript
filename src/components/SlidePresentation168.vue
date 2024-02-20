<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Array revisités - shift()</div>
    <div class="content">
      <p>
        Ainsi, puisque shift() est très similaire à pop() dans la mesure où
        shift() commence à supprimer un élément d'un tableau au début, nous
        pouvons maintenant écrire notre exemple de liste de tâches que j'ai
        montré plus tôt avec pop() en utilisant shift().
      </p>
      <MonacoEditor
        code='const t&acirc;ches&Aacute;faire = ["faire le petit d&eacute;jeuner", "amener les enfants &agrave; l&apos;&eacute;cole", "faire des courses"];'
        editorIndex="46"
      />
    </div>
  </div>
</template>

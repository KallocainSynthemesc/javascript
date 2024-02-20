<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">while Loops - exercise</div>
    <div class="content">
      <p>
        Comptez de 1 à 100 en utilisant une boucle while et affichez chaque
        étape sur la console avec console.log().
      </p>
      <MonacoEditor
        code="let monlist = [10,20,30,40,50,60]
i = 0
// utiliser monlist.length pour obtenir la longueur de la liste"
        editorIndex="18"
      />
    </div>
  </div>
</template>

<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Clean Code - Noms de variables</div>
    <div class="content">
      <p>Existe-t-il un meilleur nom de variable à la place de x ??</p>
      <MonacoEditor
        code='let livres = ["Caligula","Les Fleurs du mal", "L&apos;Immoraliste", "Le P&egrave;re Goriot"]
for(let x of livres)
{
  console.log("Le livre actuel est " + x );
}'
        editorIndex="38"
      />
    </div>
  </div>
</template>

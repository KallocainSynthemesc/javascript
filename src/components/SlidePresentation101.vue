<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">for in Loops - exemple</div>
    <div class="content">
      <p>imprimer tous les éléments d'une liste en utilisant une boucle for</p>

      <MonacoEditor
        code='let array = ["spam", "eggs", "ham"];
for (x in array){
  console.log(array[x]);  
}
'
        editorIndex="19"
      />
    </div>
  </div>
</template>

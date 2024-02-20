<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Ajout de nouvelles propriétés</div>
    <div class="content">
      <p>
        Vous pouvez ajouter de nouvelles propriétés à un objet existant en lui
        donnant simplement une valeur.
      </p>
      <MonacoEditor
        code='const person = {
  fname:"Kilian",
  lname:"Schropp",
  age: 28
};

person.nationality = "German"; 

console.log(person)
'
        editorIndex="26"
      />
    </div>
  </div>
</template>

<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Suppression des propriétés</div>
    <div class="content">
      <p>Le mot clé delete supprime une propriété d'un objet</p>
      <MonacoEditor
        code='const person = {
  firstName: "Kilian",
  lastName: "Schropp",
  age: 28,
  eyeColor: "brown"
};

delete person.age;
//ou 
delete person["eyeColor"]

console.log(person)
'
        editorIndex="27"
      />
    </div>
  </div>
</template>

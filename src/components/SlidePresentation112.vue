<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Accès aux propriétés des objets</div>
    <div class="content">
      <p>Vous pouvez accéder aux propriétés des objets de deux manières</p>
      <MonacoEditor
        code='const person = {
  firstName: "John",
  lastName: "Doe",
  age: 50,
  eyeColor: "blue"
};

console.log(person.firstName);
console.log(person["firstName"]);
'
        editorIndex="25"
      />
    </div>
  </div>
</template>

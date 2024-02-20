<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Callback - Array.filter()</div>
    <div class="content">
      <p>
        Encore une fois, j'ai mon tableau de personnes et je veux filtrer toutes
        les personnes qui ont moins de 30 ans. Pouvez-vous implémenter la
        callback fonction ?
      </p>
      <MonacoEditor
        code='function Person(prenom, nom, age )
{
  this.prenom = prenom;
  this.nom = nom;
  this.age = age;
}

const kilian = new Person("Kilian", "Schropp", 28);
const dupond = new Person("Alex", "Dupond", 41);
const berta = new Person("Berta", "Huber", 70);
const barbara = new Person("Barbara", "M&uuml;ller", 55);

const personArray = [barbara, dupond, kilian, berta];

function checkAge(obj1,obj2){

}

console.log(personArray);'
        editorIndex="51"
      />
    </div>
  </div>
</template>

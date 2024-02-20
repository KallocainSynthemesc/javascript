<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Callback - Array.sort()</div>
    <div class="content">
      <p>
        J'ai maintenant un tableau d'objets personnes. Je veux pouvoir trier par
        prénom, nom et âge. Pouvez-vous implémenter les fonctions de comparaison
        et appeler la méthode sort() avec chacune d'entre elles ?
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

function compareNom(obj1,obj2){

}

function compareAge(obj1,obj2){
  
}

function comparePrenom(obj1,obj2){
  
}

console.log(personArray);'
        editorIndex="50"
      />
    </div>
  </div>
</template>

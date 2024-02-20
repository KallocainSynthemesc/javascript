<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Clean Code - Noms de variables</div>
    <div class="content">
      <p>Puis-je raccourcir les noms d'attributs dans un objet ?</p>
      <MonacoEditor
        code='function Person(first, last, age, eyecolor) {
  this.prenomDePerson = first;
  this.nomDePerson = last;
  this.ageDePerson = age;
  this.couleurYeuxDePerson = eyecolor;
  this.nomCompletDePerson = function() {
    return this.prenomDePerson + " " + this.nomDePerson;
  };
}

const me = new Person("Kilian", "Schropp", 28, "brown")
console.log(me.nomCompletDePerson());'
        editorIndex="39"
      />
    </div>
  </div>
</template>

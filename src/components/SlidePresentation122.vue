<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Ajout d'une méthode à un constructeur</div>
    <div class="content">
      <p>Votre fonction constructeur peut également définir des méthodes</p>
      <MonacoEditor
        code='function Person(first, last, age, eyecolor) {
  this.firstName = first;
  this.lastName = last;
  this.age = age;
  this.eyeColor = eyecolor;
  this.name = function() {
    return this.firstName + " " + this.lastName;
  };
}

let me = new Person("Kilian", "Schropp", 28, "brown");
console.log(me.name());'
        editorIndex="33"
      />
    </div>
  </div>
</template>

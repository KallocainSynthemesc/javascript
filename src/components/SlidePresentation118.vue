<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Constructeurs d'objets</div>
    <div class="content">
      <p>
        Parfois, nous avons besoin d'un "plan" pour créer plusieurs objets du
        même "type". La façon de créer un "type d'objet" est d'utiliser une
        fonction de construction d'objet.
      </p>
      <MonacoEditor
        code='function Person(first, last, age, eye) {
  this.firstName = first;
  this.lastName = last;
  this.age = age;
  this.eyeColor = eye;
}

const myFather = new Person("Josef", "Schneider", 50, "blue");
const myMother = new Person("Maria", "M&uuml;ller", 48, "green");

console.log(myFather)
console.log(myMother)
'
        editorIndex="30"
      />
    </div>
  </div>
</template>

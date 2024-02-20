<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Object methods</div>
    <div class="content">
      <MonacoEditor
        code='const person = {
  firstName: "John",
  lastName : "Doe",
  id       : 5566,
  fullName : function() {
    return this.firstName + " " + this.lastName;
  },
  age(){
    return 28; //&Ccedil;a marche aussi bien
  }
};

console.log(person.firstName); //acc&egrave;s aux property
console.log(person.lastName); //acc&egrave;s aux property
console.log(person.fullName()); //appel de m&eacute;thode
console.log(person.age());//appel de m&eacute;thode
'
        editorIndex="31"
      />
    </div>
  </div>
</template>

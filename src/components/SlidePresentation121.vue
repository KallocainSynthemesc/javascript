<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Object methods - Getter et Setter</div>
    <div class="content">
      <MonacoEditor
        code='const person = {
  firstName: "John",
  lastName: "Doe",
  language: "en",
  age: 28,
  get fullName() { //mot-cl&eacute; get avec nom de m&eacute;thode
    return this.firstName + " " + this.lastName;
  },
  set currentAge(currentAge){
    this.age = currentAge;
  },
  get currentAge(){
    return this.age;
  }
};

console.log(person.fullName) //Remarquez que nous n&apos;avons plus besoin de ( ).
person.currentAge = 30;
console.log(person.age); //Il est toujours possible d&apos;acc&eacute;der directement &agrave; la propri&eacute;t&eacute;
console.log(person.currentAge); //et par appel de m&eacute;thode'
        editorIndex="32"
      />
    </div>
  </div>
</template>

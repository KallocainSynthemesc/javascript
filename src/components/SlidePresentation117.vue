<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">this - mot-clé</div>
    <div class="content">
      <MonacoEditor
        code='const person = {
  firstName: "Kilian",
  lastName : "Schropp",
  id       : 5566,
  fullName : function(firstName, lastName) {
    if(firstName == undefined || lastName == undefined){
        return this.firstName + " " + this.lastName;
    }
    return firstName + " " + lastName;
  }
};

console.log(person.fullName());
console.log(person.fullName("someone", "other"));
'
        editorIndex="29"
      />
    </div>
  </div>
</template>

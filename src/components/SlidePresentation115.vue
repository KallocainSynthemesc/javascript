<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Objets imbriqués</div>
    <div class="content">
      <p>Les valeurs d'un objet peuvent être un autre objet</p>
      <MonacoEditor
        code='person = {
  name:"Kilian",
  age:28,
  languages: {
    lan:"german",
    lan2:"english",
    lan3:"french"
  }
}

console.log(person)

//Vous pouvez acc&eacute;der aux objets imbriqu&eacute;s en utilisant 
//la notation par points ou la notation par parenth&egrave;ses

console.log(person.languages.lan);
//ou 
console.log(person.languages["lan"]);
//ou
console.log(person["languages"]["lan"]);
//ou 
let p1 = "languages";
let p2 = "lan";
console.log(person[p1][p2]);
'
        editorIndex="28"
      />
    </div>
  </div>
</template>

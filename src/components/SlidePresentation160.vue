<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Strings revisités - toLowerCase() / toUpperCase()</div>
    <div class="content">
      <p>
        Nous utilisons souvent les fonctions toUpperCase() et toLowerCase() pour
        valider les entrées des utilisateurs. Comme la comparaison est sensible
        à la casse, il suffit de changer la saisie en majuscule ou en minuscule
        et de ne comparer que le contenu de la chaîne.
      </p>
      <MonacoEditor
        code='const input = "admin";

function processInput(data){
  const admin = "ADMIN";
    if(data.toUpperCase() === admin){
      console.log("Vous &ecirc;tes administrateur");
    }
    else{
      console.log("Vous &ecirc;tes " + user);
    }
}

processInput(input);
'
        editorIndex="43"
      />
    </div>
  </div>
</template>

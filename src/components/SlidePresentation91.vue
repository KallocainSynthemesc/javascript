<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">if/else Ternary Expression - Exercice</div>
    <div class="content">
      <p>
        <b
          >Exercice : Pouvez-vous diminuer le nombre de ligne avec des tests
          ternary ?</b
        >
      </p>
      <MonacoEditor
        code='let hour = 22;
let pays = "Allemagne"; //ou France

let greeting;
if (hour &lt; 9) {
  if(pays === "Allemagne"){
    greeting = "Guten Morgen";
  }
  else{
    greeting = "bonne matin&eacute;e";
  }
}
else if(hour &lt; 18){
  if(pays === "Allemagne"){
    greeting = "Guten Tag";
  }
  else{
    greeting = "bonne journ&eacute;e";
  }
}
else{
  if(pays === "Allemagne"){
    greeting = "Guten Abend";
  }
  else{
    greeting = "bonne soir&eacute;e";
  }
}

console.log(greeting);'
        editorIndex="13"
      />
    </div>
  </div>
</template>

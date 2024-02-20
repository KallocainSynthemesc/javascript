<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Classic if/else</div>
    <div class="content">
      <p>
        Cet exemple utilise le numéro du jour de la semaine pour calculer le nom
        du jour de la semaine.
      </p>
      <MonacoEditor
        code='let result;
let day = new Date().getDay();

if(day === 0){
  result = "Dimanche";
}
else if(day === 1){
  result = "Lundi";
}
else if(day === 2){
  result = "Mardi";
}
else if(day === 3){
  result = "Mercredi";
}
else if(day === 4){
  result = "Jeudi";
}
else if(day == 5){
  result = "Vendredi";
}
else if(day == 6){
  result = "Samedi";
}

console.log(result);'
        editorIndex="15"
      />
    </div>
  </div>
</template>

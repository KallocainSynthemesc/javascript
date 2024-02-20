<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Switch</div>
    <div class="content">
      <p>Cet exemple utilise le switch</p>
      <MonacoEditor
        code='let day;
switch (new Date().getDay()) {
  case 0:
    day = "Dimanche";
    break;
  case 1:
    day = "Lundi";
    break;
  case 2:
     day = "Mardi";
    break;
  case 3:
    day = "Mercredi";
    break;
  case 4:
    day = "Jeudi";
    break;
  case 5:
    day = "Vendredi";
    break;
  case 6:
    day = "Samedi";
}

console.log(day);'
        editorIndex="16"
      />
    </div>
  </div>
</template>

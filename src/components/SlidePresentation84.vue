<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">if Tests - Format général</div>
    <div class="content">
      <MonacoEditor
        code='let direction = "Toulouse";
if (direction === "Toulouse"){
  console.log("aller &agrave; gauche");
}
else if (direction === "Chapiteau"){
  console.log("aller &agrave; droite");
}
else{
  console.log("ne bouge pas");
}
'
        editorIndex="8"
      />
    </div>
  </div>
</template>

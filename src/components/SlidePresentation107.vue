<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Loop - break, continue</div>
    <div class="content">
      <MonacoEditor
        code="for (let i = 0; i &lt; 10; i++) {
  if(i === 8){
    break; //arr&ecirc;te la boucle
  }
  if (i % 2 === 0) {
    continue; //saute une it&eacute;ration
  }
  console.log(i);
}
"
        editorIndex="23"
      />
    </div>
  </div>
</template>

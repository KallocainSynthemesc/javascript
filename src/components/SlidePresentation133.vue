<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Clean Code - Noms de variables</div>
    <div class="content">
      <p>Qu'est-ce que cela signifie, et pouvez-vous être plus clair ?</p>
      <MonacoEditor
        code='let dsl = "Pardon, je suis occup&eacute;.";
let r1 = "Je n&apos;ai rien &agrave; faire";
let qQchAFaire= true;
if(qQchAFaire){
  console.log(dsl);
}
else{
  console.log(r1);
}'
        editorIndex="36"
      />
    </div>
  </div>
</template>

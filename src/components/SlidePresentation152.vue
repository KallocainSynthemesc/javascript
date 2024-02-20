<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Clean Code - Noms de variables</div>
    <div class="content">
      <p>Puis-je retravailler le code pour qu'il fonctionne sans drapeau ?</p>
      <MonacoEditor
        code="function multiplyOrSum(num1, num2, isMulitply){
  if (isMulitply){
    return num1 * num2;
  }
  else{
    return num1 + num2;
  }
}

console.log(multiplyOrSum(2,5,true));
console.log(multiplyOrSum(2,5,false));"
        editorIndex="40"
      />
    </div>
  </div>
</template>

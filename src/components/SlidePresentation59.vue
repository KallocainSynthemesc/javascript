<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Functions - function invocation</div>
    <div class="content">
      <MonacoEditor
        code="const square = function(x) {
  return x * x;
};

console.log(square(12)); //&lt;-- function invocation
let result = square(4); //&lt;--- une autre invocation de fonction
console.log(result)

function multiply(p1, p2) { //&lt;-- d&eacute;claration de fonction classique
  return p1 * p2;   // La fonction renvoie le produit de p1 et p2
}

console.log(multiply(3,4))"
        editorIndex="6"
      />
    </div>
  </div>
</template>

<style scoped></style>

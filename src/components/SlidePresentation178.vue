<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Array revisités - includes()</div>
    <div class="content">
      <p>
        Quelqu'un a écrit une fonction contains qui vérifie si un élément est
        dans un tableau. Peut-on modifier le code en utilisant la fonction
        intégrée includes() ?
      </p>
      <MonacoEditor
        code="function contains(arr, element) {
    for (var i = 0; i &lt; arr.length; i++) {
        if (arr[i] === element) {
            return true;
        }
    }
    return false;
}
arr = [2, 5, 9, 6];
console.log(contains(arr, 5));"
        editorIndex="49"
      />
    </div>
  </div>
</template>

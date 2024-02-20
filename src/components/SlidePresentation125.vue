<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">AutoBoxing</div>
    <div class="content">
      <p>
        Le boxing consiste à envelopper une valeur primitive dans un objet.
        Lorsque vous traitez un type primitif comme s'il s'agissait d'un objet,
        par exemple en faisant appel à la fonction toLowerCase, JavaScript
        englobe le type primitif dans l'objet correspondant.
      </p>
      <MonacoEditor
        code='const name = "KILIAN";
let objName = name.toLowerCase();
console.log("value: " + objName + ", type: " + typeof(objName));

//c&apos;est la m&ecirc;me chose que de faire
objName = new Object(name)
console.log("value: " + objName + ", type: " + typeof(objName));
objName = objName.toLowerCase();
const primitiveString = objName.valueOf();
console.log("value: " + primitiveString + ", type: " + typeof(primitiveString));

'
        editorIndex="34"
      />
    </div>
  </div>
</template>

<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Data Types - Booleans</div>
    <div class="content">
      <p>
        Les valeurs suivantes se convertissent en, et donc fonctionnent comme,
        false. Toutes les autres valeurs sont converties en, et fonctionnent
        comme, true
      </p>
      <MonacoEditor
        code='var undef = undefined;
var nichts = null;
var zero = 0;
var minusZero = -0;
var notANumber = NaN;
var emptyString = ""; // the empty string
var normalTrue = true;
var normalFalse = false;
console.log("undef in boolean is: " + Boolean(undef)); //casting to boolean
console.log("nichts in boolean is: " + Boolean(nichts));
console.log("zero in boolean is: " + Boolean(zero));
console.log("minusZero in boolean is: " + Boolean(minusZero));
console.log("notANumber in boolean is: " + Boolean(notANumber));
console.log("emptyString in boolean is: " + Boolean(emptyString));
console.log("normalTrue in boolean is: " + Boolean(normalTrue));
console.log("normalFalse in boolean is: " + Boolean(normalFalse));'
        editorIndex="4"
      />
    </div>
  </div>
</template>

<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Opérateurs arithmétiques</div>
    <div class="content">
      <p>Calcule le salaire mensuel</p>
      <MonacoEditor
        code='var salaryBrut = 32000;
var salaryNet, salaryMonthlyNet;
//mettre le calcul ici
console.log("The netto year salary is " + salaryNet);
console.log("The netto monthly salary is " + salaryMonthlyNet);'
      />
    </div>
  </div>
</template>

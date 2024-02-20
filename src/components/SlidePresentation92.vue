<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">if/else chained condition - Exercice</div>
    <div class="content">
      <p>
        Le coût d'entrée dans un parc pour enfants est de 10€ pour toute
        personne âgée de 4 à 12 ans. Les personnes plus âgées ne paient que 6€.
        Écrivez un <b>test if</b> utilisant <b>&&</b> qui vérifie la tranche
        d'âge et ajuste le prix en conséquence.
      </p>
      <MonacoEditor
        code='let age = 8;
let price = 6;//&euro;
//Placez la logique if ici en utilisant &amp;&amp; pour encha&icirc;ner les tests.
console.log("Le prix d&apos;entr&eacute;e est de " + price);'
        editorIndex="14"
      />
    </div>
  </div>
</template>

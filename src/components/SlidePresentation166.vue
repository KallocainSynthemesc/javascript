<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Array revisités - pop()</div>
    <div class="content">
      <p>
        Souvent, vous verrez que pop() est utilisé lorsqu'il existe une liste
        d'actions qui doivent être traitées et retirées de la liste lorsqu'elles
        sont effectuées. L'exemple suivant est une démonstration naïve de ce
        concept.
      </p>
      <MonacoEditor
        code='const t&acirc;ches&Aacute;faire = ["faire des courses", "amener les enfants &agrave; l&apos;&eacute;cole", "faire le petit d&eacute;jeuner"];
while(t&acirc;ches&Aacute;faire.length !== 0){
    let t&acirc;che = t&acirc;ches&Aacute;faire.pop();
    console.log("Je viens de " + t&acirc;che + " et " +t&acirc;ches&Aacute;faire.length+" t&acirc;che a faire");
}
console.log(t&acirc;ches&Aacute;faire);'
        editorIndex="45"
      />
    </div>
  </div>
</template>

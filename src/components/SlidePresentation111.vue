<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Object Literals</div>
    <div class="content">
      <p>
        <b>Exercice</b> : Créez un objet de vous-même en utilisant des Object
        literals. Quels sont les attributs qu'il pourrait être intéressant de
        connaître à votre sujet ? Exemple : <b>prénom, nom de famille, sexe</b>
      </p>
      <MonacoEditor
        code='let person = {
  firstName : "mettez votre pr&eacute;nom ici"
  //ajouter des champs suppl&eacute;mentaires &agrave; l&apos;objet
}
console.log(person);
'
        editorIndex="24"
      />
    </div>
  </div>
</template>

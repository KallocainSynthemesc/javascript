<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <!--slide 78-->
  <div class="slide">
    <div class="heading">Loop</div>
    <div class="content">
      <p>
        La plupart du temps, nous devons faire une boucle du début à la fin. Si
        nous n'avons pas besoin de quelque chose de sophistiqué, il suffit
        d'utiliser la boucle "for of".
      </p>
      <MonacoEditor
        code='let array = ["Paris", "Toulouse", "Lyon", "Moissac", "Montauban", "Albi", "Figeac", "Caussade", "M&uuml;nchen", "Stuttgart", "N&uuml;rnberg"];

for(let ville of array){
  console.log(ville); //eazy
}
'
        editorIndex="22"
      />
    </div>
  </div>
</template>

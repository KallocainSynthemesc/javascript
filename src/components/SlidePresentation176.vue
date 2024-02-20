<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">Array revisités - reverse()</div>
    <div class="content">
      <p>
        En connaissant sort() et reverse(), pouvez-vous maintenant trier une
        liste de mots de Z à A ?
      </p>
      <MonacoEditor
        code='const fruits = ["Banana", "Orange", "Apple", "Mango"];'
        editorIndex="48"
      />
    </div>
  </div>
</template>

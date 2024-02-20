<script setup>
import MonacoEditor from "@/components/interactive/MonacoEditor.vue";
</script>
<template>
  <div class="slide">
    <div class="heading">For Of Loop</div>
    <div class="content">
      <div
        style="
          background: #ffffff;
          overflow: auto;
          width: auto;
          border: solid gray;
          border-width: 0.1em 0.1em 0.1em 0.8em;
          padding: 0.2em 0.6em;
        "
      >
        <pre style="margin: 0; line-height: 125%">
                  <span style="color: #000080; font-weight: bold">for</span> (variable of iterable) {
                    <span style="color: #008800; font-style: italic">// code block to be executed</span>
                  }</pre>
      </div>
      <MonacoEditor
        code='const cars = ["BMW", "Volvo", "Mini"];

for (let x of cars) {
  console.log(x);
}
'
        editorIndex="21"
      />
    </div>
  </div>
</template>

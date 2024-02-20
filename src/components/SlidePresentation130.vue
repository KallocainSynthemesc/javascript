<template>
  <div class="slide">
    <div class="heading">Clean Code - Noms de variables</div>
    <div class="content">
      <p><b>Évitez les abréviations lors de la création de variables</b></p>
      <br />
      <p>Mal:</p>
      <div
        style="
          background: #ffc5c5;
          overflow: auto;
          width: auto;
          border: solid #4a0000;
          border-width: 0.1em 0.1em 0.1em 0.8em;
          padding: 0.2em 0.6em;
        "
      >
        <pre
          style="margin: 0; line-height: 125%"
        ><span style="color: #008800; font-weight: bold">let</span> cat <span style="color: #333333">=</span> <span style="background-color: #fff0f0">&#39;Niveau 5 category&#39;</span>; <span style="color: #888888">//cat ou category??</span></pre>
      </div>
      <br />
      <p>Bien:</p>
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
        <pre
          style="margin: 0; line-height: 125%"
        ><span style="color: #008800; font-weight: bold">let</span> category <span style="color: #333333">=</span> <span style="background-color: #fff0f0">&#39;Niveau 5 category&#39;</span>;</pre>
      </div>
      <img
        src="../assets/illustrations/catOrCategory.svg"
        class="html-css-logo"
        style="left: 60%; top: 25%; height: 60%"
      />
    </div>
  </div>
</template>

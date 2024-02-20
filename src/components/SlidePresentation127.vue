<template>
  <div class="slide">
    <div class="heading">Clean Code - Noms de variables</div>
    <div class="content">
      <p><b>Évitez les noms à une seule lettre</b></p>
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
        ><span style="color: #008800; font-weight: bold">let</span> n <span style="color: #333333">=</span> <span style="background-color: #fff0f0">&#39;Kilian&#39;</span>;</pre>
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
        ><span style="color: #008800; font-weight: bold">let</span> nom <span style="color: #333333">=</span> <span style="background-color: #fff0f0">&#39;Kilian&#39;</span></pre>
      </div>
      <br />
      <p>Une exception est bien sûr un compteur d'index</p>
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
                <span style="color: #008800; font-weight: bold">for</span> (<span style="color: #008800; font-weight: bold">let</span> i <span style="color: #333333">=</span> <span style="color: #0000DD; font-weight: bold">0</span>; i <span style="color: #333333">&lt;</span> cars.length; i<span style="color: #333333">++</span>) {
                  console.log(i);
                } </pre>
      </div>
    </div>
  </div>
</template>

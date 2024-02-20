<template>
  <div class="slide">
    <div class="heading">Clean Code - Noms de variables</div>
    <div class="content">
      <p><b>Éviter la cartographie mentale</b></p>
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
        <pre style="margin: 0; line-height: 125%">
                  <span style="color: #008800; font-weight: bold">const</span> endroits <span style="color: #333333">=</span> [<span style="background-color: #fff0f0">&quot;Austin&quot;</span>, <span style="background-color: #fff0f0">&quot;New York&quot;</span>, <span style="background-color: #fff0f0">&quot;San Francisco&quot;</span>];
                  <span style="color: #008800; font-weight: bold">for</span> (<span style="color: #008800; font-weight: bold">let</span> e of endroits){
                    console.log(e); <span style="color: #888888">//que signifie &quot;e&quot; ici</span>
                  }

                  <span style="color: #008800; font-weight: bold">for</span> (<span style="color: #008800; font-weight: bold">let</span> e <span style="color: #008800; font-weight: bold">in</span> endroits){
                    console.log(e) <span style="color: #888888">//et qu&#39;est-ce que &quot;e&quot; ici</span>
                  }</pre>
      </div>
      <img
        src="../assets/illustrations/mentalMap.svg"
        class="html-css-logo"
        style="left: 55%; top: 45%; height: 50%; width: 40%"
      />
    </div>
  </div>
</template>

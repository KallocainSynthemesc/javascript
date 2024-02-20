<template>
  <div class="slide">
    <div class="heading">Clean Code - Noms de variables</div>
    <div class="content">
      <p><b>Utilisez des noms interrogeables et explicatives</b></p>
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
                  <span style="color: #888888">// Qu&#39;est-ce que c&#39;est que 86400000?</span>
                  setTimeout(misAFeu, <span style="color: #0000DD; font-weight: bold">86400000</span>);</pre>
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
        <pre style="margin: 0; line-height: 125%">
                  <span style="color: #888888">// Déclarez-les comme des constantes nommées capitalisées.</span>
                  <span style="color: #008800; font-weight: bold">const</span> MILLISECONDES_PAR_JOUR <span style="color: #333333">=</span> <span style="color: #0000DD; font-weight: bold">86400000</span>;

                  setTimeout(misAFeu, MILLISECONDES_PAR_JOUR);</pre>
      </div>
    </div>
  </div>
</template>

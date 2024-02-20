<template>
  <div class="slide">
    <div class="heading">For Loop</div>
    <div class="content">
      <p>L'instruction for crée une boucle avec 3 expressions facultatives</p>
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
                  <span style="color: #000080; font-weight: bold">for</span> (expression <span style="color: #0000FF">1</span>; expression <span style="color: #0000FF">2</span>; expression <span style="color: #0000FF">3</span>) {
                    <span style="color: #008800; font-style: italic">// code block to be executed</span>
                  }</pre>
      </div>
      <p>
        <b>L'expression 1</b> est exécutée (une fois) avant l'exécution du bloc
        de code.
      </p>
      <p>
        <b>L'expression 2</b> définit la condition d'exécution du bloc de code.
      </p>
      <p>
        <b>L'expression 3</b> est exécutée (à chaque fois) après l'exécution du
        bloc de code.
      </p>
      <div class="flex-container">
        <div>
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
                      <span style="color: #000080; font-weight: bold">for</span> (<span style="color: #000080; font-weight: bold">let</span> i = <span style="color: #0000FF">0</span>; i &lt; <span style="color: #0000FF">5</span>; i++) {
                        text += <span style="color: #0000FF">&quot;Le numéro est &quot;</span> + i + <span style="color: #0000FF">&quot;&lt;br&gt;&quot;</span>;
                      }</pre>
          </div>
        </div>
        <div>
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
                      <span style="color: #000080; font-weight: bold">for</span>(;;){ <span style="color: #008800; font-style: italic">//tourne à l&#39;infini</span>
                        console.log(<span style="color: #0000FF">&quot;in for loop&quot;</span>);
                      }</pre>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

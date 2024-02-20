<template>
  <div class="slide">
    <div class="heading">Strings revisités - includes()</div>
    <div class="content">
      <p>
        La méthode includes() renvoie true si une chaîne contient une chaîne
        spécifiée. Sinon, elle renvoie false.
      </p>
      <p><b>Syntax:</b></p>
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
        >string<span style="color: #333333">.</span>includes(searchvalue, start)</pre>
      </div>
      <br />
      <p>Vérifie si une chaîne de caractères comprend "monde":</p>
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
                  <span style="color: #008800; font-weight: bold">let</span> text <span style="color: #333333">=</span> <span style="background-color: #fff0f0">&quot;Bonjour le monde, bienvenue dans l&#39;univers.&quot;</span>;
                  <span style="color: #008800; font-weight: bold">let</span> result <span style="color: #333333">=</span> text.includes(<span style="background-color: #fff0f0">&quot;monde&quot;</span>);</pre>
      </div>
      <br />
      <p>Commencez à la position 12 :</p>
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
                  <span style="color: #008800; font-weight: bold">let</span> text <span style="color: #333333">=</span> <span style="background-color: #fff0f0">&quot;Bonjour le monde, bienvenue dans l&#39;univers.&quot;</span>;
                  <span style="color: #008800; font-weight: bold">let</span> result <span style="color: #333333">=</span> text.includes(<span style="background-color: #fff0f0">&quot;monde&quot;</span>, <span style="color: #0000DD; font-weight: bold">12</span>);</pre>
      </div>
    </div>
  </div>
</template>

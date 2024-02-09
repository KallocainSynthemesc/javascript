<template>
  <div class="slide">
    <div class="heading">Declaration - let</div>
    <div class="content">
      <p>
        La manière la plus simple d'utiliser <b>let</b> est un simple
        remplacement à la place de <b>var</b>
      </p>
      <p>
        Les variables définies avec let ne peuvent pas être redéclarées. Vous ne
        pouvez pas redéclarer accidentellement une variable. Avec let, vous ne
        pouvez pas faire ceci
      </p>
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
                  <span style="color: #0000ff">let</span> x = <span style="color: #a31515">&quot;John Doe&quot;</span> ;
                  <span style="color: #0000ff">let</span> x = 0 ; <span style="color: #008000">// Erreur de syntaxe : &#39;x&#39; a déjà été déclaré.</span></pre>
      </div>
      <p>Avec var, vous pouvez :</p>
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
                  <span style="color: #0000ff">var</span> x = <span style="color: #a31515">&quot;John Doe&quot;</span>;
                  <span style="color: #0000ff">var</span> x = 0;</pre>
      </div>
    </div>
  </div>
</template>

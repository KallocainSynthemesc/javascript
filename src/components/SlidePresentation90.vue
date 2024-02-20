<template>
  <div class="slide">
    <div class="heading">if/else Ternary Expression</div>
    <div class="content">
      <p>
        Parfois, les éléments d'une déclaration sont si simples qu'il semble
        exagéré de les répartir sur plusieurs lignes.
      </p>
      <p>
        Javascript nous offre un format d'expression qui nous permet de faire
        des if/else dans une seule expression.
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
condition ? exprIfTrue : exprIfFalse</pre
        >
      </div>

      <p>Navigation exemple</p>
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
                  <span style="color: #000080; font-weight: bold">let</span> direction = <span style="color: #0000FF">&quot;Toulouse&quot;</span>;
                  <span style="color: #000080; font-weight: bold">let</span> result = direction === <span style="color: #0000FF">&quot;Toulouse&quot;</span> ? <span style="color: #0000FF">&quot;aller à gauche&quot;</span> : <span style="color: #0000FF">&quot;aller à droite&quot;</span>
                  console.log(result);</pre>
      </div>
    </div>
  </div>
</template>

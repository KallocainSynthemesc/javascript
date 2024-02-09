<template>
  <div class="slide">
    <div class="heading">Statements</div>
    <div class="content">
      <p>
        Les instructions (statements) sont des phrases ou des commandes
        JavaScript. Tout comme les phrases françaises sont terminées et séparées
        les unes des autres par des points, les instructions JavaScript sont
        terminées par des points-virgules. Les instructions sont exécutées pour
        que quelque chose se produise
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
                  <span style="color: #0000ff">var</span> hello = <span style="color: #a31515">&quot;Hello, world&quot;</span>;
                  myfunc(42, <span style="color: #a31515">&quot;O&#39;Reilly&quot;</span>);
                  <span style="color: #0000ff">var</span> a = 1;
                  <span style="color: #0000ff">var</span> name = <span style="color: #a31515">&quot;Elphaba&quot;</span>;
                  <span style="color: #0000ff">var</span> b = a / 25.0;
                  <span style="color: #0000ff">if</span> (a == b) { console.log(a); }
                </pre>
      </div>
      <br />
      <p>
        Une instruction composée qui utilise des accolades pour marquer un bloc
        de code, tel qu'un test conditionnel ou une boucle, n'a pas besoin de
        point-virgule après l'accolade fermante.
      </p>
    </div>
  </div>
</template>

<style scoped></style>

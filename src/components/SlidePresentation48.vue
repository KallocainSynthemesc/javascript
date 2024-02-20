<template>
  <div class="slide">
    <div class="heading">Creating Arrays</div>
    <div class="content">
      <p>
        La façon la plus simple de créer un tableau est d'utiliser un littéral
        de tableau, qui est simplement une liste d'éléments de tableau séparés
        par des virgules entre crochets
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
                  <span style="color: #0000ff">var</span> empty = []; <span style="color: #008000">// Un tableau sans éléments</span>
                  <span style="color: #0000ff">var</span> primes = [2, 3, 5, 7, 11]; <span style="color: #008000">// Un tableau avec 5 éléments numériques</span>
                  <span style="color: #0000ff">var</span> misc = [ 1.1, <span style="color: #0000ff">true</span>, <span style="color: #a31515">&quot;a&quot;</span>, ]; <span style="color: #008000">// 3 éléments de différents types + virgule de fin de ligne</span></pre>
      </div>
      <p>
        Les valeurs d'un littéral de tableau ne doivent pas nécessairement être
        des constantes ; elles peuvent être des expressions arbitraires
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
                  <span style="color: #0000ff">var</span> base = 1024;
                  <span style="color: #0000ff">var</span> table = [base, base+1, base+2, base+3];</pre>
      </div>
      <p>
        Si vous omettez une valeur d'un littéral de tableau, l'élément omis
        reçoit la valeur undefined
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
                  <span style="color: #0000ff">var</span> count = [1,,3]; <span style="color: #008000">// An array with 3 elements, the middle one undefined.</span>
                  <span style="color: #0000ff">var</span> undefs = [,,]; <span style="color: #008000">// An array with 2 elements, both undefined.</span></pre>
      </div>
    </div>
  </div>
</template>

<style scoped></style>

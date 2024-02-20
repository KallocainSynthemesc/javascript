<template>
  <div class="slide">
    <div class="heading">Callback - Array.sort()</div>
    <div class="content">
      <p>
        Si je veux trier par ordre alphabétique de Z à A, il suffit d'écrire une
        fonction de comparaison qui compare les chaînes de caractères. Pour
        cela, j'utilise la fonction intégrée
        <a
          href="https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Global_Objects/String/localeCompare"
          >localeCompare()</a
        >.
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
                  <span style="color: #008800; font-weight: bold">const</span> fruits <span style="color: #333333">=</span> [<span style="background-color: #fff0f0">&quot;Banana&quot;</span>, <span style="background-color: #fff0f0">&quot;Apple&quot;</span>, <span style="background-color: #fff0f0">&quot;Ananas&quot;</span>, <span style="background-color: #fff0f0">&quot;Blueberry&quot;</span>, <span style="background-color: #fff0f0">&quot;Mango&quot;</span>];

                  <span style="color: #008800; font-weight: bold">function</span> compare(a,b){
                    <span style="color: #008800; font-weight: bold">return</span> b.localeCompare(a);
                  }
                  fruits.sort(compare)
                  console.log(fruits)</pre>
      </div>
    </div>
  </div>
</template>

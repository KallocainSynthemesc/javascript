<template>
  <div class="slide">
    <div class="heading">Array revisités - sort()</div>
    <div class="content">
      <p>La fonction sort() trie les éléments d'un tableau.</p>
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
                  <span style="color: #008800; font-weight: bold">const</span> fruits <span style="color: #333333">=</span> [<span style="background-color: #fff0f0">&quot;Banana&quot;</span>, <span style="background-color: #fff0f0">&quot;Orange&quot;</span>, <span style="background-color: #fff0f0">&quot;Apple&quot;</span>, <span style="background-color: #fff0f0">&quot;Mango&quot;</span>];
                  fruits.sort();
                  console.log(fruits); <span style="color: #888888">//[ &#39;Apple&#39;, &#39;Banana&#39;, &#39;Mango&#39;, &#39;Orange&#39; ]</span></pre>
      </div>
      <br />
      <p>
        Dans l'exemple ci-dessus, le tableau est trié par ordre alphabétique.
      </p>
      <p>
        Nous disposons toutefois d'un moyen plus puissant de trier. Nous pouvons
        définir nous-mêmes la condition par laquelle elle est triée. Nous y
        regarderons de plus près une fois que je vous aurai montré comment
        fonctionnent les callbacks.
      </p>
    </div>
  </div>
</template>

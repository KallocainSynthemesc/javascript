<template>
  <div class="slide">
    <div class="heading">Array revisités - push()</div>
    <div class="content">
      <p>
        La méthode <b>push()</b> ajoute de nouveaux éléments à la fin d'un
        tableau.
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
                  <span style="color: #008800; font-weight: bold">const</span> fruits <span style="color: #333333">=</span> [<span style="background-color: #fff0f0">&quot;Banana&quot;</span>, <span style="background-color: #fff0f0">&quot;Orange&quot;</span>, <span style="background-color: #fff0f0">&quot;Apple&quot;</span>, <span style="background-color: #fff0f0">&quot;Mango&quot;</span>];
                  fruits.push(<span style="background-color: #fff0f0">&quot;Kiwi&quot;</span>);
                  console.log(fruits);
                  fruits.push(<span style="background-color: #fff0f0">&quot;Strawberry&quot;</span>, <span style="background-color: #fff0f0">&quot;Lemon&quot;</span>); 
                  console.log(fruits);

                  <span style="color: #888888">// est la même chose que</span>

                  fruits[fruits.length]  <span style="color: #333333">=</span> <span style="background-color: #fff0f0">&quot;Blueberry&quot;</span>;
                  <span style="color: #888888">//sauf que je ne peux pas ajouter plusieurs éléments à la fois avec la notation de l&#39;index.</span>
                  console.log(fruits);</pre>
      </div>
    </div>
  </div>
</template>

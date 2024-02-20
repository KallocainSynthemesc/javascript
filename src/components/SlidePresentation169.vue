<template>
  <div class="slide">
    <div class="heading">Array revisités - unshift()</div>
    <div class="content">
      <p>
        La méthode unshift() ajoute de nouveaux éléments au début d'un tableau.
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
                  fruits.unshift(<span style="background-color: #fff0f0">&quot;Lemon&quot;</span>,<span style="background-color: #fff0f0">&quot;Pineapple&quot;</span>);
                  console.log(fruits) <span style="color: #888888">//[ &#39;Lemon&#39;, &#39;Pineapple&#39;, &#39;Banana&#39;, &#39;Orange&#39;, &#39;Apple&#39;, &#39;Mango&#39; ]</span></pre>
      </div>
    </div>
  </div>
</template>

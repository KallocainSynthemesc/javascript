<template>
  <div class="slide">
    <div class="heading">Array revisités - includes()</div>
    <div class="content">
      <p>
        La méthode includes() renvoie un résultat positif si un tableau contient
        une valeur spécifiée. Elle renvoie false si la valeur n'est pas trouvée.
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
                  <span style="color: #008800; font-weight: bold">const</span> result <span style="color: #333333">=</span> fruits.includes(<span style="background-color: #fff0f0">&quot;Mango&quot;</span>);
                  console.log(result); <span style="color: #888888">//true</span>
                  </pre>
      </div>
      <br />
      <p>Commencez la recherche à la position 3 :</p>
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
                  fruits.includes(<span style="background-color: #fff0f0">&quot;Banana&quot;</span>, <span style="color: #0000DD; font-weight: bold">3</span>);</pre>
      </div>
    </div>
  </div>
</template>

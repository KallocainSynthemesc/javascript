<template>
  <div class="slide">
    <div class="heading">Array revisités - concat()</div>
    <div class="content">
      <p>
        La méthode concat() concatène (joint) deux tableaux ou plus. Elle
        renvoie un nouveau tableau, contenant les tableaux joints et ne modifie
        pas les tableaux existants.
      </p>
      <p>Exemple:</p>
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
                <span style="color: #008800; font-weight: bold">const</span> arr1 <span style="color: #333333">=</span> [<span style="background-color: #fff0f0">&quot;Cecilie&quot;</span>, <span style="background-color: #fff0f0">&quot;Lone&quot;</span>];
                <span style="color: #008800; font-weight: bold">const</span> arr2 <span style="color: #333333">=</span> [<span style="background-color: #fff0f0">&quot;Emil&quot;</span>, <span style="background-color: #fff0f0">&quot;Tobias&quot;</span>, <span style="background-color: #fff0f0">&quot;Linus&quot;</span>];
                <span style="color: #008800; font-weight: bold">const</span> children <span style="color: #333333">=</span> arr1.concat(arr2);
                console.log(children) <span style="color: #888888">//[ &#39;Cecilie&#39;, &#39;Lone&#39;, &#39;Emil&#39;, &#39;Tobias&#39;, &#39;Linus&#39; ]</span></pre>
      </div>
    </div>
  </div>
</template>

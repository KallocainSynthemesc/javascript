<template>
  <div class="slide">
    <div class="heading">Callback - Array.sort()</div>
    <div class="content">
      <p>
        Un petit rappel : La méthode sort() trie un tableau par ordre
        alphabétique.
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
                  fruits.sort();
                  console.log(fruits) <span style="color: #888888">//[ &#39;Apple&#39;, &#39;Banana&#39;, &#39;Mango&#39;, &#39;Orange&#39; ]</span>
                </pre>
      </div>
      <br />
      <p>
        Par défaut, la fonction sort() trie les valeurs sous forme de chaînes de
        caractères. Si les nombres sont triés comme des chaînes de caractères,
        "25" est plus grand que "100", car "2" est plus grand que "1".
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
                  <span style="color: #008800; font-weight: bold">const</span> numbers <span style="color: #333333">=</span> [<span style="color: #0000DD; font-weight: bold">25</span>, <span style="color: #0000DD; font-weight: bold">100</span>, <span style="color: #0000DD; font-weight: bold">40</span>, <span style="color: #0000DD; font-weight: bold">3</span>];
                  numbers.sort();
                  console.log(numbers) <span style="color: #888888">//[ 100, 25, 3, 40 ] ?</span></pre>
      </div>
    </div>
  </div>
</template>

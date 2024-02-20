<template>
  <div class="slide">
    <div class="heading">Strings revisités - split()</div>
    <div class="content">
      <p>
        La méthode split() divise une chaîne de caractères en un tableau de
        sous-chaînes.
      </p>
      <br />
      <p>Syntax:</p>
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
string.split(separator, limit)</pre
        >
      </div>
      <br />
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
                  <span style="color: #008800; font-weight: bold">let</span> text <span style="color: #333333">=</span> <span style="background-color: #fff0f0">&quot;Comment ça va aujourd&#39;hui ?&quot;</span>;
                  <span style="color: #008800; font-weight: bold">let</span> words <span style="color: #333333">=</span> text.split(<span style="background-color: #fff0f0">&quot; &quot;</span>);
                  <span style="color: #008800; font-weight: bold">let</span> word <span style="color: #333333">=</span> words[<span style="color: #0000DD; font-weight: bold">1</span>];
                  console.log(word);
                  words <span style="color: #333333">=</span> text.split(<span style="background-color: #fff0f0">&quot; &quot;</span>, <span style="color: #0000DD; font-weight: bold">3</span>);
                  console.log(words)</pre>
      </div>
    </div>
  </div>
</template>

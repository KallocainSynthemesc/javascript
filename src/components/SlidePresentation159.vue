<template>
  <div class="slide">
    <div class="heading">Strings revisités - toLowerCase() / toUpperCase()</div>
    <div class="content">
      <p>
        La méthode <b>toLowerCase()</b> convertit une chaîne de caractères en
        lettres <b>minuscules</b>. La méthode <b>toUpperCase()</b> convertit une
        chaîne de caractères en lettres <b>majuscules</b>.
      </p>
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
                  <span style="color: #008800; font-weight: bold">let</span> text <span style="color: #333333">=</span> <span style="background-color: #fff0f0">&quot;Hello World!&quot;</span>;
                  <span style="color: #008800; font-weight: bold">let</span> result <span style="color: #333333">=</span> text.toUpperCase(); 
                  console.log(result); <span style="color: #888888">//HELLO WORLD!</span>
                  result <span style="color: #333333">=</span> text.toLowerCase();
                  console.log(result); <span style="color: #888888">//hello world!</span></pre>
      </div>
    </div>
  </div>
</template>

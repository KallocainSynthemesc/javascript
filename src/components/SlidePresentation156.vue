<template>
  <div class="slide">
    <div class="heading">Strings revisités - length</div>
    <div class="content">
      <p>
        La propriété length renvoie la longueur d'une chaîne de caractères. La
        propriété length d'une chaîne vide est 0.
      </p>
      <p>
        C'est la même chose qu'avec un tableau car, en interne, une String est
        un tableau de caractères (lettres).
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
                <span style="color: #008800; font-weight: bold">let</span> length <span style="color: #333333">=</span> text.length;
                <span style="color: #008800; font-weight: bold">let</span> lettreH <span style="color: #333333">=</span> text[<span style="color: #0000DD; font-weight: bold">0</span>];
                console.log(length)
                console.log(lettreH)</pre>
      </div>
    </div>
  </div>
</template>

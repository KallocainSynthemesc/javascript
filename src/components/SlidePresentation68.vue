<template>
  <div class="slide">
    <div class="heading">Functions - Paramètre Valeur par défaut</div>
    <div class="content">
      <p>
        Si nous appelons la fonction sans argument, elle utilise la valeur par
        défaut
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
                  <span style="color: #000080; font-weight: bold">function</span> multiply(x, y=<span style="color: #0000FF">4</span>) { <span style="color: #000080; font-weight: bold">return</span> x * y; } <span style="color: #008800; font-style: italic">//Le deuxième paramètre est un paramètre par défaut</span>
                  console.log(multiply(<span style="color: #0000FF">8</span>)); <span style="color: #008800; font-style: italic">//result: 32</span></pre>
      </div>
      <br />
      <img
        src="../assets/illustrations/defaultParameter.svg"
        style="width: 35%"
      />
    </div>
  </div>
</template>

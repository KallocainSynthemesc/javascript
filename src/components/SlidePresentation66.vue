<template>
  <div class="slide">
    <div class="heading">Functions - Nombre d'arguments</div>
    <div class="content">
      <p>
        Si nous définissons une fonction qui prend un paramètre mais que nous
        l'appelons avec trois, le langage ne se plaint pas
      </p>
      <p>Cette fonction attend 1 argument, et reçoit 3 arguments :</p>
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
                <span style="color: #000080; font-weight: bold">function</span> square(x) { <span style="color: #000080; font-weight: bold">return</span> x * x; }
                console.log(square(<span style="color: #0000FF">4</span>, <span style="color: #000080; font-weight: bold">true</span>, <span style="color: #0000FF">&quot;hedgehog&quot;</span>));</pre>
      </div>
      <br />
      <p>Cette fonction attend 2 arguments, mais n'en reçoit qu'un seul:</p>
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
                  <span style="color: #000080; font-weight: bold">function</span> multiply(x, y) { <span style="color: #000080; font-weight: bold">return</span> x * y; }
                  console.log(multiply(<span style="color: #0000FF">4</span>)); <span style="color: #008800; font-style: italic">//le deuxième paramètre devient undefined</span></pre>
      </div>
    </div>
  </div>
</template>

<style scoped></style>

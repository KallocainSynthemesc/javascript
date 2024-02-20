<template>
  <div class="slide">
    <div class="heading">Callback - Array.forEach()</div>
    <div class="content">
      <p>Notez que la fonction avant prend 3 arguments :</p>
      <ul>
        <li>La valeur de l'élément</li>
        <li>L'index de l'élément</li>
        <li>Le tableau lui-même</li>
      </ul>
      <br />
      <p>
        Dans la méthode Array.forEach(), nous ne pouvons fournir qu'un seul
        argument.
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
                  <span style="color: #008800; font-weight: bold">const</span> numbers <span style="color: #333333">=</span> [<span style="color: #0000DD; font-weight: bold">45</span>, <span style="color: #0000DD; font-weight: bold">4</span>, <span style="color: #0000DD; font-weight: bold">9</span>, <span style="color: #0000DD; font-weight: bold">16</span>, <span style="color: #0000DD; font-weight: bold">25</span>];
                  numbers.forEach(display);

                  <span style="color: #008800; font-weight: bold">function</span> display(value) {
                    console.log(<span style="background-color: #fff0f0">&quot;Value: &quot;</span> <span style="color: #333333">+</span> value )
                  }</pre>
      </div>
    </div>
  </div>
</template>

<template>
  <div class="slide">
    <div class="heading">Callback - Array.forEach()</div>
    <div class="content">
      <p>
        Rappelez-vous la fonction forEach() que j'ai brièvement présentée et
        jamais vraiment expliquée. C'est le moment !
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

                  <span style="color: #008800; font-weight: bold">function</span> display(value, index, array) {
                    console.log(<span style="background-color: #fff0f0">&quot;Value: &quot;</span> <span style="color: #333333">+</span> value <span style="color: #333333">+</span> <span style="background-color: #fff0f0">&quot;, index: &quot;</span> <span style="color: #333333">+</span> index)
                  }</pre>
      </div>
      <br />
      <p>
        Comme nous n'avons pas implémenté la méthode forEach(), nous pouvons
        jeter un coup d'œil rapide dans la documentation
        <a
          href="https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach#description"
          >mdn</a
        >
        et voir comment elle se comporte.
      </p>
    </div>
  </div>
</template>

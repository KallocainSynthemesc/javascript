<template>
  <div class="slide">
    <div class="heading">Callback - Array.filter()</div>
    <div class="content">
      <p>
        La méthode filter() crée un nouveau tableau rempli d'éléments qui
        passent un test fourni par une fonction.
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
                  <span style="color: #008800; font-weight: bold">const</span> ages <span style="color: #333333">=</span> [<span style="color: #0000DD; font-weight: bold">32</span>, <span style="color: #0000DD; font-weight: bold">33</span>, <span style="color: #0000DD; font-weight: bold">16</span>, <span style="color: #0000DD; font-weight: bold">40</span>];
                  <span style="color: #008800; font-weight: bold">const</span> result <span style="color: #333333">=</span> ages.filter(checkAdult);

                  <span style="color: #008800; font-weight: bold">function</span> checkAdult(age) {
                    <span style="color: #008800; font-weight: bold">return</span> age <span style="color: #333333">&gt;=</span> <span style="color: #0000DD; font-weight: bold">18</span>;
                  }

                  console.log(result);</pre>
      </div>
      <p>
        Encore une fois, jetons un coup d'œil à la
        <a
          href="https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Global_Objects/Array/filter"
          >documentation</a
        >.
      </p>
    </div>
  </div>
</template>

<template>
  <div class="slide">
    <div class="heading">Callback - Array.sort()</div>
    <div class="content">
      <p>
        Belle fonction, Kilian! sort() ne peut même pas trier les chiffres !
        Mais attendez, lisons la
        <a
          href="https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Global_Objects/Array/sort#description"
          >documentation</a
        >
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
                  <span style="color: #008800; font-weight: bold">const</span> numbers <span style="color: #333333">=</span> [<span style="color: #0000DD; font-weight: bold">40</span>, <span style="color: #0000DD; font-weight: bold">100</span>, <span style="color: #0000DD; font-weight: bold">1</span>, <span style="color: #0000DD; font-weight: bold">5</span>, <span style="color: #0000DD; font-weight: bold">25</span>, <span style="color: #0000DD; font-weight: bold">10</span>];
                  numbers.sort(compare);

                  <span style="color: #008800; font-weight: bold">function</span> compare(a,b){
                      <span style="color: #008800; font-weight: bold">return</span> a - b
                  }

                  console.log(numbers); <span style="color: #888888">//[ 1, 5, 10, 25, 40, 100 ]</span></pre>
      </div>
      <p>
        Nous devons simplement indiquer à la fonction sort() comment elle doit
        trier. La façon de faire est de fournir une fonction qui compare deux
        valeurs
      </p>
    </div>
  </div>
</template>

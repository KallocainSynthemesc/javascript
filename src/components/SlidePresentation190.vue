<template>
  <div class="slide">
    <div class="heading">Callback - Array.sort()</div>
    <div class="content">
      <p>Mais pourquoi ça marche ?</p>
      <p>
        Voici un algorithme de tri écrit à la main. Remarquez-vous des
        similitudes avec l'exemple précédent ?
      </p>
      <div style="overflow-y: scroll; height: 85%">
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
  
                    <span style="color: #008800; font-weight: bold">function</span> compare(a,b){
                      <span style="color: #008800; font-weight: bold">return</span> a <span style="color: #333333">&gt;</span> b
                    }
  
                    <span style="color: #008800; font-weight: bold">function</span> sortArray(array, callback) {
                      <span style="color: #008800; font-weight: bold">var</span> temp <span style="color: #333333">=</span> <span style="color: #0000DD; font-weight: bold">0</span>;
                      <span style="color: #008800; font-weight: bold">for</span> (<span style="color: #008800; font-weight: bold">var</span> i <span style="color: #333333">=</span> <span style="color: #0000DD; font-weight: bold">0</span>; i <span style="color: #333333">&lt;</span> array.length; i<span style="color: #333333">++</span>) {
                        <span style="color: #008800; font-weight: bold">for</span> (<span style="color: #008800; font-weight: bold">var</span> j <span style="color: #333333">=</span> i; j <span style="color: #333333">&lt;</span> array.length; j<span style="color: #333333">++</span>) {
                          <span style="color: #008800; font-weight: bold">if</span> (callback(array[i],array[j])) {
                            temp <span style="color: #333333">=</span> array[j];
                            array[j] <span style="color: #333333">=</span> array[i];
                            array[i] <span style="color: #333333">=</span> temp;
                          }
                        }
                      }
                      <span style="color: #008800; font-weight: bold">return</span> array;
                    }
  
                    console.log(sortArray(numbers, compare))</pre>
        </div>
      </div>
    </div>
  </div>
</template>

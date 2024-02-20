<template>
  <div class="slide">
    <div class="heading">Clean Code - Functions</div>
    <div class="content">
      <p><b>Les fonctions doivent faire une chose</b> (si possible)</p>
      <p>Mal:</p>
      <div style="overflow-y: scroll; height: 85%">
        <div
          style="
            background: #ffc5c5;
            overflow: auto;
            width: auto;
            border: solid #4a0000;
            border-width: 0.1em 0.1em 0.1em 0.8em;
            padding: 0.2em 0.6em;
          "
        >
          <pre style="margin: 0; line-height: 125%">
                    <span style="color: #008800; font-weight: bold">var</span> array <span style="color: #333333">=</span> [<span style="background-color: #fff0f0">&quot;Manish&quot;</span>,<span style="background-color: #fff0f0">&quot;Chandan&quot;</span>,<span style="background-color: #fff0f0">&quot;Piyush&quot;</span>,<span style="background-color: #fff0f0">&quot;Sunil&quot;</span>,<span style="background-color: #fff0f0">&quot;Pankaj&quot;</span>,<span style="background-color: #fff0f0">&quot;Piyush&quot;</span>,<span style="background-color: #fff0f0">&quot;Pankaj&quot;</span>,<span style="background-color: #fff0f0">&quot;Tiny&quot;</span>,<span style="background-color: #fff0f0">&quot;Chandan&quot;</span>,<span style="background-color: #fff0f0">&quot;Manish&quot;</span>];

                    <span style="color: #008800; font-weight: bold">function</span> removeDuplicates(array){
                      <span style="color: #008800; font-weight: bold">let</span> storage <span style="color: #333333">=</span> [array[<span style="color: #0000DD; font-weight: bold">0</span>]];
                      <span style="color: #008800; font-weight: bold">for</span>(<span style="color: #008800; font-weight: bold">let</span> i <span style="color: #333333">=</span> <span style="color: #0000DD; font-weight: bold">1</span>; i <span style="color: #333333">&lt;</span> array.length; i<span style="color: #333333">++</span>){
                        <span style="color: #008800; font-weight: bold">let</span> contains <span style="color: #333333">=</span> <span style="color: #008800; font-weight: bold">false</span>;
                        <span style="color: #008800; font-weight: bold">for</span>(<span style="color: #008800; font-weight: bold">let</span> item of storage){
                          <span style="color: #008800; font-weight: bold">if</span>(array[i] <span style="color: #333333">===</span> item){
                            contains <span style="color: #333333">=</span> <span style="color: #008800; font-weight: bold">true</span>;
                          }
                        }
                        <span style="color: #008800; font-weight: bold">if</span>(contains <span style="color: #333333">===</span> <span style="color: #008800; font-weight: bold">false</span>){
                          storage[storage.length] <span style="color: #333333">=</span> array[i];
                        }
                      }
                      <span style="color: #008800; font-weight: bold">return</span> storage;
                    }    

                    console.log(removeDuplicates(array));</pre>
        </div>
      </div>
    </div>
  </div>
</template>

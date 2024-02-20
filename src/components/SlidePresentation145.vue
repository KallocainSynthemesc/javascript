<template>
  <div class="slide">
    <div class="heading">Clean Code - Functions</div>
    <div class="content">
      <p><b>Les fonctions doivent faire une chose</b> (si possible)</p>
      <p>Bien:</p>
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
                    <span style="color: #000080; font-weight: bold">var</span> array = [<span style="color: #0000FF">&quot;Manish&quot;</span>,<span style="color: #0000FF">&quot;Chandan&quot;</span>,<span style="color: #0000FF">&quot;Piyush&quot;</span>,<span style="color: #0000FF">&quot;Sunil&quot;</span>,<span style="color: #0000FF">&quot;Pankaj&quot;</span>,<span style="color: #0000FF">&quot;Piyush&quot;</span>,<span style="color: #0000FF">&quot;Pankaj&quot;</span>,<span style="color: #0000FF">&quot;Tiny&quot;</span>,<span style="color: #0000FF">&quot;Chandan&quot;</span>,<span style="color: #0000FF">&quot;Manish&quot;</span>];

                    <span style="color: #000080; font-weight: bold">function</span> removeDuplicates(array){
                      <span style="color: #000080; font-weight: bold">let</span> storage = [array[<span style="color: #0000FF">0</span>]];
                      <span style="color: #000080; font-weight: bold">for</span>(<span style="color: #000080; font-weight: bold">let</span> i = <span style="color: #0000FF">1</span>; i &lt; array.length; i++){
                        <span style="color: #000080; font-weight: bold">if</span>(contains(array[i], storage) === <span style="color: #000080; font-weight: bold">false</span>){
                          storage[storage.length] = array[i];
                        }
                      }
                      <span style="color: #000080; font-weight: bold">return</span> storage;
                    }    

                    <span style="color: #000080; font-weight: bold">function</span> contains(elem, arr){
                      <span style="color: #000080; font-weight: bold">for</span>(<span style="color: #000080; font-weight: bold">let</span> item of arr){
                        <span style="color: #000080; font-weight: bold">if</span>(elem === item){
                          <span style="color: #000080; font-weight: bold">return</span> <span style="color: #000080; font-weight: bold">true</span>;
                        }
                      }
                      <span style="color: #000080; font-weight: bold">return</span> <span style="color: #000080; font-weight: bold">false</span>;
                    }

                    console.log(removeDuplicates(array));</pre>
        </div>
      </div>
    </div>
  </div>
</template>

<template>
  <div class="slide">
    <div class="heading">Callback - Array.filter()</div>
    <div class="content">
      <p>
        Jetons un coup d'œil à une fonction d'exemple écrite à la main qui fait
        la même chose. Pouvez-vous trouver les similarités ?
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
                    <span style="color: #008800; font-weight: bold">const</span> ages <span style="color: #333333">=</span> [<span style="color: #0000DD; font-weight: bold">32</span>, <span style="color: #0000DD; font-weight: bold">33</span>, <span style="color: #0000DD; font-weight: bold">16</span>, <span style="color: #0000DD; font-weight: bold">40</span>];
  
                    <span style="color: #008800; font-weight: bold">function</span> checkAdult(age, index, array) {
                      <span style="color: #008800; font-weight: bold">return</span> age <span style="color: #333333">&gt;=</span> <span style="color: #0000DD; font-weight: bold">18</span>;
                    }
  
                    <span style="color: #008800; font-weight: bold">function</span> filter(array, callback){
                      <span style="color: #008800; font-weight: bold">let</span> storage <span style="color: #333333">=</span> [array[<span style="color: #0000DD; font-weight: bold">0</span>]];
                      <span style="color: #008800; font-weight: bold">for</span>(<span style="color: #008800; font-weight: bold">let</span> i <span style="color: #333333">=</span> <span style="color: #0000DD; font-weight: bold">1</span>; i <span style="color: #333333">&lt;</span> array.length; i<span style="color: #333333">++</span>){
                        <span style="color: #008800; font-weight: bold">if</span>(callback(array[i])){
                          storage.push(array[i]);
                        }
                      }
                      <span style="color: #008800; font-weight: bold">return</span> storage;
                    }    
                    console.log(filter(ages, checkAdult));</pre>
        </div>
      </div>
    </div>
  </div>
</template>

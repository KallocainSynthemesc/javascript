<template>
  <div class="slide">
    <div class="heading">Clean Code - Noms de variables</div>
    <div class="content">
      <p><b>Éviter la cartographie mentale</b></p>
      <p>Bien:</p>
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
                  <span style="color: #008800; font-weight: bold">const</span> endroits <span style="color: #333333">=</span> [<span style="background-color: #fff0f0">&quot;Austin&quot;</span>, <span style="background-color: #fff0f0">&quot;New York&quot;</span>, <span style="background-color: #fff0f0">&quot;San Francisco&quot;</span>];
                  <span style="color: #008800; font-weight: bold">for</span> (<span style="color: #008800; font-weight: bold">let</span> endroit of endroits){
                    console.log(endroit); <span style="color: #888888">//endroit est plus claire ce que la variable représente</span>
                  }

                  <span style="color: #008800; font-weight: bold">for</span> (<span style="color: #008800; font-weight: bold">let</span> index <span style="color: #008800; font-weight: bold">in</span> endroits){
                    <span style="color: #888888">//un simple &quot;i&quot; serait également acceptable car il est bien connu dans la communauté des développeurs.</span>
                    console.log(index)
                  }</pre>
      </div>
    </div>
  </div>
</template>

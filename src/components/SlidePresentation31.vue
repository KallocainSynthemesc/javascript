<template>
  <div class="slide">
    <div class="heading">Data Types - Integers</div>
    <div class="content">
      <p>Solution:</p>
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
                  <span style="color: #008000">//exemple simple</span>
                  <span style="color: #0000ff">var</span> a = 39;
                  <span style="color: #0000ff">var</span> b = 25;
                  <span style="color: #0000ff">var</span> third = a;
                  a = b;  
                  b = third;  
                  console.log(<span style="color: #a31515">&quot;variable a=&quot;</span> +a+ <span style="color: #a31515">&quot; ,variable b=&quot;</span> +b);  

                  <span style="color: #008000">//exemple plus complexe</span>
                  a = 45;
                  b = 105;
                  a=a+b;  
                  b=a-b;  
                  a=a-b;  
                  console.log(<span style="color: #a31515">&quot;variable a=&quot;</span> +a+ <span style="color: #a31515">&quot; ,variable b=&quot;</span> +b);   
                </pre>
      </div>
    </div>
  </div>
</template>

<style scoped></style>

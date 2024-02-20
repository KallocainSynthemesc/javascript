<template>
  <div class="slide">
    <div class="heading">Loop - break, continue</div>
    <div class="content">
      <p>L'instruction break "saute" d'une boucle.</p>
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
                  <span style="color: #000080; font-weight: bold">for</span> (<span style="color: #000080; font-weight: bold">let</span> i = <span style="color: #0000FF">0</span>; i &lt; <span style="color: #0000FF">10</span>; i++) {
                    <span style="color: #000080; font-weight: bold">if</span> (i === <span style="color: #0000FF">3</span>) {
                      <span style="color: #000080; font-weight: bold">break</span>; 
                    }
                    console.log(i);
                  }</pre>
      </div>
      <br />
      <p>L'instruction continue "saute" une itération de la boucle.</p>
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
                  <span style="color: #000080; font-weight: bold">for</span> (<span style="color: #000080; font-weight: bold">let</span> i = <span style="color: #0000FF">0</span>; i &lt; <span style="color: #0000FF">10</span>; i++) {
                    <span style="color: #000080; font-weight: bold">if</span> (i === <span style="color: #0000FF">3</span>) { <span style="color: #000080; font-weight: bold">continue</span>; }
                    console.log(i);
                  }</pre>
      </div>
    </div>
  </div>
</template>

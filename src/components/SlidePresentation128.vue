<template>
  <div class="slide">
    <div class="heading">Clean Code - Noms de variables</div>
    <div class="content">
      <p><b>Utilisez des noms de variables significatifs et prononçables</b></p>
      <br />
      <p>Mal:</p>
      <!-- HTML generated using hilite.me -->
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
        <pre
          style="margin: 0; line-height: 125%"
        ><span style="color: #008800; font-weight: bold">const</span> yyyymmdstr <span style="color: #333333">=</span> <span style="color: #008800; font-weight: bold">new</span> <span style="color: #007020">Date</span>().toISOString().slice(<span style="color: #0000DD; font-weight: bold">0</span>, <span style="color: #0000DD; font-weight: bold">10</span>);</pre>
      </div>
      <br />
      <p>Bien:</p>
      <!-- HTML generated using hilite.me -->
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
        <pre
          style="margin: 0; line-height: 125%"
        ><span style="color: #008800; font-weight: bold">const</span> dateActuelle <span style="color: #333333">=</span> <span style="color: #008800; font-weight: bold">new</span> <span style="color: #007020">Date</span>().toISOString().slice(<span style="color: #0000DD; font-weight: bold">0</span>, <span style="color: #0000DD; font-weight: bold">10</span>);</pre>
      </div>
    </div>
  </div>
</template>

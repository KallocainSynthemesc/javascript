<template>
  <div class="slide">
    <div class="heading">Clean Code - Functions</div>
    <div class="content">
      <p><b>Les noms de fonction doivent dire ce qu'ils font</b></p>
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
                  <span style="color: #008800; font-weight: bold">function</span> ajouterMoisADate(mois, date) {
                    <span style="color: #008800; font-weight: bold">return</span> newDate <span style="color: #333333">=</span> <span style="color: #008800; font-weight: bold">new</span> <span style="color: #007020">Date</span>(date.setMonth(date.getMonth()<span style="color: #333333">+</span>mois));
                  }

                  <span style="color: #008800; font-weight: bold">const</span> date <span style="color: #333333">=</span> <span style="color: #008800; font-weight: bold">new</span> <span style="color: #007020">Date</span>();
                  ajouterMoisADate(<span style="color: #0000DD; font-weight: bold">1</span>, date);</pre>
      </div>
    </div>
  </div>
</template>

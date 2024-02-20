<template>
  <div class="slide">
    <div class="heading">Clean Code - Functions</div>
    <div class="content">
      <p><b>Les noms de fonction doivent dire ce qu'ils font</b></p>
      <p>Mal:</p>
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
                  <span style="color: #008800; font-weight: bold">function</span> ajouterÀLaDate(date, mois) {
                    <span style="color: #008800; font-weight: bold">return</span> newDate <span style="color: #333333">=</span> <span style="color: #008800; font-weight: bold">new</span> <span style="color: #007020">Date</span>(date.setMonth(date.getMonth()<span style="color: #333333">+</span>mois));
                  }

                  <span style="color: #008800; font-weight: bold">const</span> date <span style="color: #333333">=</span> <span style="color: #008800; font-weight: bold">new</span> <span style="color: #007020">Date</span>();

                  <span style="color: #888888">// Il est difficile de dire à partir du nom de la fonction ce qui est ajouté</span>
                  ajouterÀLaDate(date, <span style="color: #0000DD; font-weight: bold">1</span>);</pre>
      </div>
    </div>
  </div>
</template>

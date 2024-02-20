<template>
  <div class="slide">
    <div class="heading">Clean Code - Noms de variables</div>
    <div class="content">
      <p><b>Ne pas ajouter de contexte inutile</b></p>
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
                  <span style="color: #008800; font-weight: bold">const</span> Voiture <span style="color: #333333">=</span> {
                    marqueDeVoiture<span style="color: #333333">:</span> <span style="background-color: #fff0f0">&quot;Honda&quot;</span>,
                    modeleDeVoiture<span style="color: #333333">:</span> <span style="background-color: #fff0f0">&quot;Accord&quot;</span>,
                    couleurDeVoiture<span style="color: #333333">:</span> <span style="background-color: #fff0f0">&quot;Bleue&quot;</span>
                  };

                  <span style="color: #008800; font-weight: bold">function</span> peindreLaVoiture(voiture) {
                    voiture.couleurDeVoiture <span style="color: #333333">=</span> <span style="background-color: #fff0f0">&quot;Rouge&quot;</span>;
                  }</pre>
      </div>
    </div>
  </div>
</template>

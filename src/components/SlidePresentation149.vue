<template>
  <div class="slide">
    <div class="heading">Clean Code - Functions</div>
    <div class="content">
      <p><b>Refactoriser le code dupliqué</b></p>
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
                    <span style="color: #008800; font-weight: bold">function</span> afficherLaListeDesEmployes(employes) {
                      <span style="color: #008800; font-weight: bold">for</span>(<span style="color: #008800; font-weight: bold">let</span> employe of employes){
                        <span style="color: #008800; font-weight: bold">const</span> salairePrevu <span style="color: #333333">=</span> employe.calculerSalairePrevu();
                        <span style="color: #008800; font-weight: bold">const</span> experience <span style="color: #333333">=</span> employe.obtenirExperience();
                        <span style="color: #008800; font-weight: bold">const</span> donnes <span style="color: #333333">=</span> {
                          salairePrevu,
                          experience
                        };

                        <span style="color: #008800; font-weight: bold">switch</span> (employe.type) {
                          <span style="color: #008800; font-weight: bold">case</span> <span style="background-color: #fff0f0">&quot;gestionnaire&quot;</span><span style="color: #333333">:</span>
                            donnes.portfolio <span style="color: #333333">=</span> employe.obtenireProjetsMBA();
                            <span style="color: #008800; font-weight: bold">break</span>;
                          <span style="color: #008800; font-weight: bold">case</span> <span style="background-color: #fff0f0">&quot;développeur&quot;</span><span style="color: #333333">:</span>
                            donnes.lienGithub <span style="color: #333333">=</span> employe.obtenirLienGithub();
                            <span style="color: #008800; font-weight: bold">break</span>;
                        }

                        <span style="color: #008800; font-weight: bold">return</span> donnes;
                      }
                    }</pre>
        </div>
      </div>
    </div>
  </div>
</template>

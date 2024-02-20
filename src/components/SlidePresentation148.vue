<template>
  <div class="slide">
    <div class="heading">Clean Code - Functions</div>
    <div class="content">
      <p><b>Refactoriser le code dupliqué</b></p>
      <p>Mal:</p>
      <div style="overflow-y: scroll; height: 85%">
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
                    <span style="color: #008800; font-weight: bold">function</span> afficherLaListeDesDéveloppeurs(developpeurs) {
                      <span style="color: #008800; font-weight: bold">for</span>(<span style="color: #008800; font-weight: bold">let</span> developpeur of developpeurs){
                        <span style="color: #008800; font-weight: bold">const</span> salairePrevu <span style="color: #333333">=</span> developpeur.calculerSalairePrévu();
                        <span style="color: #008800; font-weight: bold">const</span> experience <span style="color: #333333">=</span> developpeur.obtenirExpérience();
                        <span style="color: #008800; font-weight: bold">const</span> lienGithub <span style="color: #333333">=</span> developpeur.obtenirLienGithub();
                        <span style="color: #008800; font-weight: bold">const</span> donnes <span style="color: #333333">=</span> {
                          salairePrevu,
                          experience,
                          lienGithub
                        };
                        <span style="color: #008800; font-weight: bold">return</span> donnes;
                      }
                    }

                    <span style="color: #008800; font-weight: bold">function</span> afficherLaListeDesGestionnaires(gestionnaires) {
                      <span style="color: #008800; font-weight: bold">for</span>(<span style="color: #008800; font-weight: bold">let</span> gestionnaire of gestionnaires){
                        <span style="color: #008800; font-weight: bold">const</span> salairePrevu <span style="color: #333333">=</span> gestionnaire.calculerSalairePrévu();
                        <span style="color: #008800; font-weight: bold">const</span> experience <span style="color: #333333">=</span> gestionnaire.obtenirExpérience();
                        <span style="color: #008800; font-weight: bold">const</span> portfolio  <span style="color: #333333">=</span> gestionnaire.obtenireProjetsMBA();
                        <span style="color: #008800; font-weight: bold">const</span> donnes <span style="color: #333333">=</span> {
                          salairePrevu,
                          experience,
                          portfolio 
                        };
                        <span style="color: #008800; font-weight: bold">return</span> donnes;
                      }
                    }</pre>
        </div>
      </div>
    </div>
  </div>
</template>

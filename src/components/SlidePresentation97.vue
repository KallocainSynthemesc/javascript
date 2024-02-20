<template>
  <div class="slide">
    <div class="heading">while Loops</div>
    <div class="content">
      <p>
        En termes simples, while exécute de manière répétée un bloc
        d'instructions (normalement indentées) tant qu'un test situé en haut de
        l'instruction continue d'être évalué à une valeur vraie.
      </p>
      <div class="flex-container">
        <div style="width: 20%">
          <p><b>Format général</b></p>
        </div>
        <div style="width: 80%">
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
                      <span style="color: #000080; font-weight: bold">while</span> (test){<span style="color: #008800; font-style: italic">//Test en boucle</span>
                        statements <span style="color: #008800; font-style: italic">// Corps de la boucle </span>
                      }</pre>
          </div>
        </div>
      </div>
      <br />
      <div class="flex-container">
        <div style="width: 20%">
          <p><b>Exemple</b></p>
        </div>
        <div style="width: 80%">
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
                      <span style="color: #000080; font-weight: bold">while</span>(<span style="color: #000080; font-weight: bold">true</span>){
                        console.log(<span style="color: #0000FF">&#39;Here we are now&#39;</span>)
                      }</pre>
          </div>
        </div>
      </div>
      <img
        src="../assets/illustrations/kurtcobain.svg"
        class="html-css-logo"
        style="width: 40%; left: 50%; top: 52%; height: unset"
      />
    </div>
  </div>
</template>

<template>
  <div class="slide">
    <div class="heading">Clean Code - Functions</div>
    <div class="content">
      <p><b>Ne pas utiliser les drapeaux comme paramètres de fonction</b></p>
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
                  <span style="color: #008800; font-weight: bold">function</span> créerUnFichier(nom) {
                    fs.create(nom);
                  }

                  <span style="color: #008800; font-weight: bold">function</span> créerUnFichierTemp(nom) {
                    créerUnFichier(`.<span style="color: #333333">/</span>temp<span style="color: #333333">/</span>${nom}`);
                  }
                  </pre>
      </div>
    </div>
  </div>
</template>

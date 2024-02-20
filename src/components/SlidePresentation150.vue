<template>
  <div class="slide">
    <div class="heading">Clean Code - Functions</div>
    <div class="content">
      <p><b>Ne pas utiliser les drapeaux comme paramètres de fonction</b></p>
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
                  <span style="color: #008800; font-weight: bold">function</span> créerUnFichier(nom, temp) {
                    <span style="color: #008800; font-weight: bold">if</span> (temp) {
                      fs.create(`.<span style="color: #333333">/</span>temp<span style="color: #333333">/</span>${nom}`);
                    } <span style="color: #008800; font-weight: bold">else</span> {
                      fs.create(nom);
                    }
                  }</pre>
      </div>
    </div>
  </div>
</template>

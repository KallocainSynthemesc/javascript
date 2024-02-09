<template>
  <div class="slide">
    <div class="heading">Declaration - Block scope and let</div>
    <div class="content">
      <p>
        Cette scope restreint l'accès à la variable déclarée à l'intérieur d'un
        bloc spécifique par les personnes extérieures à ce bloc. Le mot-clé
        <b>let</b> facilite la mise en place d'une scope de bloc pour les
        variables
      </p>
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
                {
                    <span style="color: #0000ff">let</span> x = 2 ;
                }
                <span style="color: #008000">// x ne peut PAS être utilisé ici</span>
                {
                    <span style="color: #0000ff">var</span> x = 2 ;
                }
                <span style="color: #008000">// x PEUT être utilisé ici</span></pre>
      </div>
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
                  <span style="color: #0000ff">let</span> x = 10 ;
                  <span style="color: #008000">// Ici, x est 10</span>
                  {
                      <span style="color: #0000ff">let</span> x = 2 ;
                      <span style="color: #008000">// Ici, x est 2</span>
                  }
                  <span style="color: #008000">// Ici, x est égal à 10 </span></pre>
      </div>
      <img
        src="../assets/illustrations/corsshair.svg"
        class="html-css-logo"
        style="left: 40%; top: 40%; height: 40%; width: 40%"
      />
      <img
        src="../assets/illustrations/warning.svg"
        class="html-css-logo"
        style="left: 70%; top: 63%; height: 32%"
      />
    </div>
  </div>
</template>

<template>
  <div class="slide">
    <div class="heading">Declaration - const</div>
    <div class="content">
      <p>
        Les constantes sont comme les variables, sauf que les affectations à ces
        dernières sont ignorées (la tentative de modifier une constante ne
        provoque pas d'erreur) et les tentatives de les redéclarer provoquent
        des erreurs
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
                  <span style="color: #0000ff">const</span> pi = 3.14 ; <span style="color: #008000">// Définit une constante et lui donne une valeur.</span>
                  pi = 4 ; <span style="color: #008000">// Toute affectation future à cette constante est ignorée en silence.</span>
                  <span style="color: #0000ff">const</span> pi = 4 ; <span style="color: #008000">// C&#39;est une erreur de redéclarer une constante.</span>
                  <span style="color: #0000ff">var</span> pi = 4 ; <span style="color: #008000">// C&#39;est également une erreur.</span></pre>
      </div>
      <p>Le mot-clé const se comporte fondamentalement comme le mot-clé var</p>
      <img
        src="../assets/illustrations/constant.svg"
        class="html-css-logo"
        style="left: 32%; top: 60%; height: 40%; width: 40%"
      />
    </div>
  </div>
</template>

<template>
  <div class="slide">
    <div class="heading">Constructeurs JavaScript intégrés</div>
    <div class="content">
      <p>
        JavaScript dispose de versions objet des types de données primitifs
        String, Number et Boolean. Mais il n'y a (presque) aucune raison de
        créer des objets complexes. Les valeurs primitives sont beaucoup plus
        rapides :
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
                Utiliser les littéraux de chaîne <span style="background-color: #fff0f0">&quot;&quot;</span> au lieu de <span style="color: #008800; font-weight: bold">new</span> <span style="color: #007020">String</span>().

                Utilisez les littéraux de nombres <span style="color: #0000DD; font-weight: bold">50</span> au lieu de <span style="color: #008800; font-weight: bold">new</span> <span style="color: #007020">Number</span>().

                Utiliser les littéraux booléens <span style="color: #008800; font-weight: bold">true</span> <span style="color: #333333">/</span> <span style="color: #008800; font-weight: bold">false</span> au lieu de <span style="color: #008800; font-weight: bold">new</span> <span style="color: #007020">Boolean</span>().

                Utiliser les littéraux d&#39;objet {} au lieu de <span style="color: #008800; font-weight: bold">new</span> <span style="color: #007020">Object</span>().

                Utiliser les littéraux de tableau [] au lieu de <span style="color: #008800; font-weight: bold">new</span> <span style="color: #007020">Array</span>().

                Utiliser les littéraux de motif <span style="color: #333333">/</span>()<span style="color: #333333">/</span> au lieu de <span style="color: #008800; font-weight: bold">new</span> <span style="color: #007020">RegExp</span>().

                Utiliser les expressions de fonctions () {} au lieu de <span style="color: #008800; font-weight: bold">new</span> <span style="color: #007020">Function</span>().</pre>
      </div>
    </div>
  </div>
</template>

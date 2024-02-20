<template>
  <div class="slide">
    <div class="heading">Object Literals</div>
    <div class="content">
      <p>
        Le moyen le plus simple de créer un objet est d'inclure un objet
        littéral dans votre code JavaScript. Un objet littéral est une liste de
        paires nom/valeur séparées par des virgules, entre accolades.
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
                  <span style="color: #0000ff">var</span> empty = {} ; <span style="color: #008000">// Un objet sans propriétés</span>
                  <span style="color: #0000ff">var</span> point = { x : 0, y : 0 } ; <span style="color: #008000">// Deux propriétés</span>
                  <span style="color: #0000ff">var</span> point2 = { x : point.x, y : point.y + 1 } ; <span style="color: #008000">// Des valeurs plus complexes</span>
                  <span style="color: #0000ff">var</span> book = {
                    <span style="color: #a31515">&quot;titre principal&quot;</span> : <span style="color: #a31515">&quot;JavaScript&quot;</span>, <span style="color: #008000">// Les noms des propriétés incluent des espaces,</span>
                    <span style="color: #a31515">&quot;sub-title&quot;</span> : <span style="color: #a31515">&quot;The Definitive Guide&quot;</span>, <span style="color: #008000">// et des traits d&#39;union, utilisez donc des chaînes de caractères.</span>
                    auteur : {<span style="color: #008000">// La valeur de cette propriété est</span>
                      firstname : <span style="color: #a31515">&quot;David&quot;</span>, <span style="color: #008000">//elle-même un objet. Notez que</span>
                      surname : <span style="color: #a31515">&quot;Flanagan&quot;</span>, <span style="color: #008000">// ces noms de propriétés ne sont pas cités.</span>
                    },
                  };</pre>
      </div>
    </div>
  </div>
</template>

<template>
  <div class="slide">
    <div class="heading">Array Length</div>
    <div class="content">
      <p>
        Chaque tableau possède une propriété de longueur (<b>length</b>). La
        propriété length spécifie le nombre d'éléments du tableau. Sa valeur est
        supérieure d'une unité à l'indice le plus élevé du tableau
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
                  [].length <span style="color: #008000">// =&gt; 0 : le tableau n&#39;a pas d&#39;éléments</span>
                  [<span style="color: #a31515">&#39;a&#39;</span>, <span style="color: #a31515">&#39;b&#39;</span>, <span style="color: #a31515">&#39;c&#39;</span>].length <span style="color: #008000">// =&gt; 3 : l&#39;indice le plus élevé est 2, la longueur est 3</span>
                </pre>
      </div>
      <p>
        Si vous définissez la propriété <b>length</b> à un nombre entier non
        négatif <b>n</b> inférieur à sa valeur actuelle, tous les éléments du
        tableau dont l'index est supérieur ou égal à <b>n</b> sont supprimés du
        tableau.
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
                a = [1,2,3,4,5] ; <span style="color: #008000">// On commence avec un tableau de 5 éléments.</span>
                a.length = 3 ; <span style="color: #008000">// a est maintenant [1,2,3].</span>
                a.length = 0 ; <span style="color: #008000">// Supprime tous les éléments. a est [].</span>
                a.length = 5 ; <span style="color: #008000">// La longueur est de 5, mais il n&#39;y a pas d&#39;éléments, comme new Array(5).</span>
                </pre>
      </div>
    </div>
  </div>
</template>

<style scoped></style>

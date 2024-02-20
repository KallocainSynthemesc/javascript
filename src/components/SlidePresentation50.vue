<template>
  <div class="slide">
    <div class="heading">Lecture et écriture des éléments d'un Array</div>
    <div class="content">
      <p>
        Vous accédez à un élément d'un tableau en utilisant l'opérateur
        <b>[ ]</b>. Une référence au tableau doit apparaître à gauche des
        crochets. Une expression arbitraire dont la valeur est un nombre
        <b>entier non négatif</b> doit se trouver à l'intérieur des parenthèses.
        Vous pouvez utiliser cette syntaxe pour lire et écrire la valeur d'un
        élément d'un tableau. Ainsi, les instructions suivantes sont toutes
        <b>légales</b> en JavaScript :
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
                  <span style="color: #0000ff">var</span> a = [<span style="color: #a31515">&quot;world&quot;</span>] ; <span style="color: #008000">// Commence par un tableau à un élément</span>
                  <span style="color: #0000ff">var</span> value = a[0] ; <span style="color: #008000">// Lecture de l&#39;élément 0</span>
                  a[1] = 3.14 ; <span style="color: #008000">// Écriture de l&#39;élément 1</span>
                  i = 2 ;
                  a[i] = 3 ; <span style="color: #008000">// Écriture de l&#39;élément 2</span>
                  a[i + 1] = <span style="color: #a31515">&quot;hello&quot;</span> ; <span style="color: #008000">// Écriture de l&#39;élément 3</span>
                  a[a[i]] = a[0] ; <span style="color: #008000">// Lecture des éléments 0 et 2, écriture de l&#39;élément 3</span>
                </pre>
      </div>
    </div>
  </div>
</template>

<style scoped></style>

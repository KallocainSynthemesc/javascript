<template>
  <div class="slide">
    <div class="heading">Creating Arrays</div>
    <div class="content">
      <p>
        Une autre façon de créer un tableau est d'utiliser le
        <b>constructeur</b> Array(). Je vais expliquer ce qu'est un
        <b>constructeur</b> un peu plus tard. Je n'inclus cette méthode que par
        souci d'exhaustivité. Vous pouvez invoquer ce <b>constructeur</b> de
        trois manières différentes
      </p>
      <ul>
        <li>
          <p>Appelez-le sans arguments</p>
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
            <pre
              style="margin: 0; line-height: 125%"
            ><span style="color: #0000ff">var</span> a = <span style="color: #0000ff">new</span> Array();</pre>
          </div>
        </li>
        <li>
          <p>
            L'appeler avec un seul argument numérique, qui spécifie une longueur
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
            <pre
              style="margin: 0; line-height: 125%"
            ><span style="color: #0000ff">var</span> a = <span style="color: #0000ff">new</span> Array(10);</pre>
          </div>
        </li>
        <li>
          <p>
            Spécifier explicitement deux ou plusieurs éléments de tableau ou un
            seul élément non numérique pour le tableau
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
            <pre
              style="margin: 0; line-height: 125%"
            ><span style="color: #0000ff">var</span> a = <span style="color: #0000ff">new</span> Array(5, 4, 3, 2, 1, <span style="color: #a31515">&quot;testing, testing&quot;</span>) ;</pre>
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>

<style scoped></style>

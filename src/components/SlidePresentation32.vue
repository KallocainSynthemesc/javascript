<template>
  <div class="slide">
    <div class="heading">Data Types basic - Floating-Point</div>
    <div class="content">
      <p>
        Les types de données à virgule flottante peuvent avoir un point décimal
        ; ils utilisent la syntaxe traditionnelle des nombres réels. Une valeur
        réelle est représentée par la partie intégrale du nombre, suivie d'un
        point décimal et de la partie fractionnaire du nombre
      </p>
      <p>
        Les littéraux à virgule flottante peuvent également être représentés à
        l'aide de la notation exponentielle : un nombre réel suivi de la lettre
        e (ou E), suivi d'un signe plus ou moins facultatif, suivi d'un exposant
        entier. Cette notation représente le nombre réel multiplié par 10 à la
        puissance de l'exposant
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
                  <span style="color: #008000">//Notation simple</span>
                  3.14
                  2345.789
                  .333333333333333333
                  <span style="color: #008000">//Notation scientifique/exponentielle</span>
                  6.02e23 <span style="color: #008000">// 6.02 × 1023</span>
                  1.4738223E-32 <span style="color: #008000">// 1.4738223 × 10-32</span>
                </pre>
      </div>
    </div>
  </div>
</template>

<template>
  <div class="slide">
    <div class="heading">Data Types - Integers</div>
    <div class="content">
      <p>
        Dans un programme JavaScript, un nombre entier en base 10 est écrit sous
        la forme d'une séquence de chiffres. Par exemple
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
                  <span style="color: #0000ff">var</span> zero = 0;
                  <span style="color: #0000ff">var</span> three = 3;
                  <span style="color: #0000ff">var</span> zehnmillionen = 10000000;
                </pre>
      </div>
      <p>
        Outre les littéraux entiers en base 10, JavaScript reconnaît les valeurs
        hexadécimales (base 16). Un littéral hexadécimal commence par "0x" ou
        "0X", suivi d'une chaîne de chiffres hexadécimaux.
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
                  <span style="color: #0000ff">var</span> number1 = 0xff; <span style="color: #008000">// 15*16 + 15 = 255 (base 10)</span>
                   <span style="color: #0000ff">var</span> number2 = 0xCAFE911; <span style="color: #008000">//212855057</span>
                </pre>
      </div>
      <p>
        Les nombres entiers octaux existent également en JavaScript (exemple :
        0377). Certaines implémentations JavaScript prennent en charge les
        littéraux octaux, d'autres non. Vous ne devez donc jamais l'utiliser.
      </p>
    </div>
  </div>
</template>

<style scoped></style>

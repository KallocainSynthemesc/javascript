<template>
  <div class="slide">
    <div class="heading">Declaration</div>
    <div class="content">
      <p>
        Avant d'utiliser une variable dans un programme JavaScript, vous devez
        la déclarer. Les variables sont déclarées avec le mot-clé <b>var</b>
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
                  <span style="color: #0000ff">var</span> i;
                  <span style="color: #0000ff">var</span> sum;
                </pre>
      </div>
      <p>
        Vous pouvez également déclarer plusieurs variables avec le même mot-clé
        <b>var</b>
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
                  <span style="color: #0000ff">var</span> i, sum;
                </pre>
      </div>
      <p>
        Et vous pouvez combiner la déclaration de variable avec l'initialisation
        de variable. Les détails complets sur les types de données apparaissent
        plus loin dans la présentation
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
                  <span style="color: #0000ff">var</span> message = <span style="color: #a31515">&quot;hello&quot;</span>;
                  <span style="color: #0000ff">var</span> i = 0, j = 0, k = 0;
                </pre>
      </div>
    </div>
  </div>
</template>

<style scoped></style>

<template>
  <div class="slide">
    <div class="heading">Date</div>
    <div class="content">
      <p>Les objets date sont créés avec new Date().</p>
      <p>Il existe quatre façons d'instancier (créer) une date :</p>
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
                  <span style="color: #008800; font-weight: bold">let</span> date <span style="color: #333333">=</span> <span style="color: #008800; font-weight: bold">new</span> <span style="color: #007020">Date</span>();
                  console.log(date); <span style="color: #888888">//2022-11-04T09:02:15.409Z</span></pre>
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
                  date <span style="color: #333333">=</span> <span style="color: #008800; font-weight: bold">new</span> <span style="color: #007020">Date</span>(<span style="color: #0000DD; font-weight: bold">100000000000</span>); <span style="color: #888888">//milliseconds</span>
                  console.log(date); <span style="color: #888888">//1973-03-03T09:46:40.000Z</span></pre>
      </div>
      <p>
        Tout comme nous avons commencé à compter les années après la mort de
        Jésus, nous avons commencé à compter les millisecondes après le 1er
        janvier 1970 00:00:00 UTC.
      </p>
      <p>
        L'époque actuelle du 1er janvier 1970 00:00:00 UTC a été choisie
        arbitrairement par les ingénieurs d'Unix parce qu'elle était considérée
        comme une date pratique pour travailler.
      </p>
      <img
        src="../assets/illustrations/jesus.svg"
        class="html-css-logo"
        style="left: 65%; top: 75%"
      />
    </div>
  </div>
</template>

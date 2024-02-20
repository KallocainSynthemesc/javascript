<template>
  <div class="slide">
    <div class="heading">Date</div>
    <div class="content">
      <p>Les objets date sont créés avec new Date().</p>
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
                  <span style="color: #008800; font-weight: bold">const</span> date <span style="color: #333333">=</span> <span style="color: #008800; font-weight: bold">new</span> <span style="color: #007020">Date</span>(<span style="background-color: #fff0f0">&quot;2015-03-25&quot;</span>);
                  console.log(date); <span style="color: #888888">//2015-03-25T00:00:00.000Z</span>
                  </pre>
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
                  <span style="color: #888888">//new Date(année, mois, jour, heures, minutes, secondes, millisecondes);</span>
                  <span style="color: #008800; font-weight: bold">const</span> date <span style="color: #333333">=</span> <span style="color: #008800; font-weight: bold">new</span> <span style="color: #007020">Date</span>(<span style="color: #0000DD; font-weight: bold">2018</span>, <span style="color: #0000DD; font-weight: bold">11</span>, <span style="color: #0000DD; font-weight: bold">24</span>, <span style="color: #0000DD; font-weight: bold">10</span>, <span style="color: #0000DD; font-weight: bold">33</span>, <span style="color: #0000DD; font-weight: bold">30</span>, <span style="color: #0000DD; font-weight: bold">0</span>);
                  console.log(date); <span style="color: #888888">//2018-12-24T10:33:30.000Z</span></pre>
      </div>
      <br />
      <p>
        Le mois de la classe Date est basé sur un zéro. Le mois de janvier est
        égal à 0. Donc, si vous transmettez un mois égal à 1, vous dites à la
        date qu'elle est le mois de février.
      </p>
    </div>
  </div>
</template>

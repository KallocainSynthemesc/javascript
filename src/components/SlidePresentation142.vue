<template>
  <div class="slide">
    <div class="heading">Clean Code - Functions</div>
    <div class="content">
      <p><b>Arguments de fonction (idéalement 2 ou moins)</b></p>
      <p>
        Habituellement, si vous avez plus de deux arguments, votre fonction
        essaie de faire trop. Dans les cas où il n'est pas, la plupart du temps
        un objet de niveau supérieur suffira en tant que argument.
      </p>
      <p>Mal:</p>
      <div
        style="
          background: #ffc5c5;
          overflow: auto;
          width: auto;
          border: solid #4a0000;
          border-width: 0.1em 0.1em 0.1em 0.8em;
          padding: 0.2em 0.6em;
        "
      >
        <pre style="margin: 0; line-height: 125%">
                  <span style="color: #008800; font-weight: bold">let</span> titre <span style="color: #333333">=</span> <span style="background-color: #fff0f0">&quot;un titre&quot;</span>;
                  <span style="color: #008800; font-weight: bold">let</span> corps <span style="color: #333333">=</span> <span style="background-color: #fff0f0">&quot;contenu du corps&quot;</span>;
                  <span style="color: #008800; font-weight: bold">let</span> boutonTexte <span style="color: #333333">=</span> <span style="background-color: #fff0f0">&quot;Click here&quot;</span>;
                  <span style="color: #008800; font-weight: bold">let</span> annulable <span style="color: #333333">=</span> <span style="color: #008800; font-weight: bold">true</span>;
                  <span style="color: #008800; font-weight: bold">function</span> creerUnMenu(titre, corps, boutonTexte, annulable) {
                    <span style="color: #888888">// ...</span>
                  }
                  creerUnMenu(titre,corps,boutonTexte,annulable);</pre>
      </div>
      <img
        src="../assets/illustrations/peace.svg"
        class="html-css-logo"
        style="left: 60%; top: 45%; height: 50%; width: 40%"
      />
    </div>
  </div>
</template>

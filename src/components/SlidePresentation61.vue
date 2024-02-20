<template>
  <div class="slide">
    <div class="heading">Functions - Scopes</div>
    <div class="content">
      <p>
        les variables peuvent être assignées à trois endroits différents,
        correspondant à trois scopes différentes
      </p>
      <div class="flex-container">
        <div>
          <p><b>Block scope</b></p>
        </div>
        <div style="width: 80%">
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
                    {
                      <span style="color: #000080; font-weight: bold">let</span> x = <span style="color: #0000FF">2</span>;
                    }</pre>
          </div>
        </div>
      </div>
      <div class="flex-container">
        <div>
          <p><b>Block scope</b></p>
        </div>
        <div style="width: 80%">
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
                    <span style="color: #008800; font-style: italic">// le code ici ne peut PAS utiliser le nom de la voiture</span>
                    <span style="color: #000080; font-weight: bold">function</span> myFunction() {
                      <span style="color: #000080; font-weight: bold">var</span> carName = <span style="color: #0000FF">&quot;Volvo&quot;</span> ;
                      <span style="color: #008800; font-style: italic">// le code ici peut utiliser carName</span>
                    }
                    <span style="color: #008800; font-style: italic">// le code ici ne peut PAS utiliser carName</span></pre>
          </div>
        </div>
      </div>
      <div class="flex-container">
        <div>
          <p><b>Global scope</b></p>
        </div>
        <div style="width: 80%">
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
                      <span style="color: #000080; font-weight: bold">let</span> carName = <span style="color: #0000FF">&quot;Volvo&quot;</span> ;
                      <span style="color: #008800; font-style: italic">// le code ici peut utiliser carName</span>
                      <span style="color: #000080; font-weight: bold">function</span> myFunction() {
                      <span style="color: #008800; font-style: italic">// le code ici peut également utiliser carName</span>
                      }</pre>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>

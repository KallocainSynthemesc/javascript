<template>
  <div class="slide">
    <div class="heading">if Tests - Format général</div>
    <div class="content">
      <p>
        Lorsque l'instruction if s'exécute, Javascript exécute le bloc de code
        associé au premier test dont l'évaluation est vraie, ou le bloc else si
        tous les tests sont faux. La forme générale d'une instruction if
        ressemble à ceci
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
                    <span style="color: #008800; font-weight: bold">if</span> (test1){ <span style="color: #10863d"># if test</span>
                        statements1 <span style="color: #10863d"># bloc associé</span>
                    }
                    <span style="color: #008800; font-weight: bold">else if</span> (test2){ <span style="color: #10863d"># Optionnel else if</span>
                        statements2
                    }
                    <span style="color: #008800; font-weight: bold">else</span>{ <span style="color: #10863d"># Optionnel else</span>
                        statements3
                    }</pre>
      </div>
    </div>
  </div>
</template>

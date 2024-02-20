<template>
  <div class="slide">
    <div class="heading">Functions - Argument-Passing Basics</div>
    <div class="content">
      <div class="flex-container">
        <div>
          <p>
            <b
              >L'affectation des noms d'arguments à l'intérieur d'une fonction
              n'affecte pas l'appelant.</b
            >
          </p>
          <br />
          <p>
            <b>C'est un peu comme faire :</b>
          </p>
          <div
            style="
              background: #f0f0f0;
              overflow: auto;
              width: auto;
              border: solid gray;
              border-width: 0.1em 0.1em 0.1em 0.8em;
              padding: 0.2em 0.6em;
            "
          >
            <pre style="margin: 0; line-height: 125%">
                      box <span style="color: #666666">=</span> box2 <span style="color: #666666">=</span> <span style="color: #4070a0">&quot;text&quot;</span>
                      box2 <span style="color: #666666">=</span> <span style="color: #4070a0">&quot;nouveau texte&quot;</span></pre>
          </div>
        </div>
        <div style="width: 52%">
          <img
            src="../assets/illustrations/argumentAssignment.svg"
            style="width: 100%"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>

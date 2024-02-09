<template>
  <div class="slide">
    <div class="heading">Comments</div>
    <div class="content">
      <p>
        Les commentaires donnent des informations aux personnes qui lisent votre
        code. JavaScript prend en charge deux styles de commentaires. Tout texte
        entre un <b>//</b> et la fin d'une ligne est traité comme un commentaire
        et est ignoré par JavaScript. Tout texte entre les caractères
        <b>/*</b> et <b>*/</b> est également traité comme un commentaire.
      </p>
      <p class="sub-title">Exemple:</p>
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
                <span style="color: #008000">// This is a single-line comment.</span>
                <span style="color: #008000">/* This is also a comment */</span> 
                <span style="color: #008000">// and here is another comment.</span>
                <span style="color: #008000">/*</span>
                <span style="color: #008000">* This is yet another comment.</span>
                <span style="color: #008000">* It has multiple lines.</span>
                <span style="color: #008000">*/</span>
                </pre>
      </div>
    </div>
  </div>
</template>

<style scoped></style>

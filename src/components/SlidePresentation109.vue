<template>
  <div class="slide">
    <div class="heading">Objects</div>
    <div class="content">
      <p>Dans la vie réelle, une voiture est un <b>objet</b>.</p>
      <p>
        Une voiture a des <b>propriétés</b> comme le poids et la couleur, et des
        <b>méthodes</b> comme le démarrage et l'arrêt
      </p>
      <p>
        Vous avez déjà appris que les variables JavaScript sont des conteneurs
        pour les valeurs de données. Ce code attribue une valeur simple
        (Mustang) à une variable nommée voiture.
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
                  <span style="color: #0000ff">var</span> voiture = <span style="color: #a31515">&quot;Mustang&quot;</span>;</pre>
      </div>
      <p>
        Les objets sont aussi des variables. Mais les objets peuvent contenir
        plusieurs valeurs. Ce code attribue plusieurs valeurs (Mustang, 500,
        rouge) à une variable nommée voiture :
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
                  <span style="color: #0000ff">const</span> voiture= {type : <span style="color: #a31515">&quot;Mustang&quot;</span>, modele : <span style="color: #a31515">&quot;500&quot;</span>, couleur : <span style="color: #a31515">&quot;rouge&quot;</span>} ; <span style="color: #008000">//une autre façon de créer un objet.</span></pre>
      </div>
      <img
        src="../assets/illustrations/Ford_Mustang.svg"
        class="html-css-logo"
        style="left: 50%; top: 79%"
      />
    </div>
  </div>
</template>

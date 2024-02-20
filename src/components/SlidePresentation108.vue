<template>
  <div class="slide">
    <div class="heading">Objects</div>
    <div class="content">
      <p>
        Le type de données fondamental de JavaScript est l'objet. Un objet est
        une valeur composite : il regroupe plusieurs valeurs (valeurs primitives
        ou autres objets) et vous permet de stocker et de récupérer ces valeurs
        par nom. Un objet est une collection non ordonnée de propriétés, chacune
        ayant un nom et une valeur. Les noms de propriétés sont des chaînes de
        caractères, on peut donc dire que les objets font correspondre des
        chaînes de caractères à des valeurs.
      </p>
      <p>
        Toute valeur en JavaScript qui n'est <b>pas</b> un <b>string</b>, un
        <b>nombre</b>, <b>true</b>, <b>false</b>, <b>null</b> ou
        <b>undefined</b> est un objet
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
                  <span style="color: #0000ff">var</span> myCar = <span style="color: #0000ff">new</span> Object();
                  myCar.make = <span style="color: #a31515">&quot;Ford&quot;</span>;
                  myCar.model = <span style="color: #a31515">&quot;Mustang&quot;</span>;
                  myCar.year = 1969;
                </pre>
      </div>
      <img
        src="../assets/illustrations/ford.svg"
        class="html-css-logo"
        style="left: 60%; top: 56%"
      />
      <img
        src="../assets/illustrations/Ford_Mustang.svg"
        class="html-css-logo"
        style="left: 50%; top: 75%; width: 40%"
      />
    </div>
  </div>
</template>

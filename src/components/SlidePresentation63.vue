<template>
  <div class="slide">
    <div class="heading">Functions - Argument-Passing Basics</div>
    <div class="content">
      <div class="flex-container">
        <div style="width: 60%">
          <p>
            <b
              >Les arguments sont transmis en assignant automatiquement des
              objets aux noms de variables locales.
            </b>
          </p>
          <p>
            Les arguments de fonction (références à des objets partagés envoyées
            par l'appelant) ne sont qu'un autre exemple d'affectation Javascript
            à l'œuvre. Les objets passés en tant qu'arguments ne sont jamais
            copiés automatiquement.
          </p>
          <p>
            <b>C'est un peu comme faire : var box = box2 = "text"</b>
          </p>
        </div>
        <div>
          <img
            src="../assets/illustrations/argumentPassing.svg"
            style="width: 85%"
          />
        </div>
      </div>
    </div>
  </div>
</template>

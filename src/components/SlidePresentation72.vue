<template>
  <div class="slide">
    <div class="heading">Opérateurs logiques</div>
    <div class="content">
      <p>
        Il existe trois opérateurs d'expression booléenne en javascript
        (Opérateurs logiques)
      </p>
      <table class="tg" style="width: 100%; height: 50%">
        <thead>
          <tr>
            <th class="tg-0lax">
              <span style="font-weight: bold">Operator</span>
            </th>
            <th class="tg-0lax">
              <span style="font-weight: bold">Description</span>
            </th>
            <th class="tg-0lax">
              <span style="font-weight: bold">Exemple</span>
            </th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="tg-0lax">&&</td>
            <td class="tg-0lax">
              Retourne Vrai si les deux déclarations sont vraies
            </td>
            <td class="tg-0lax">x &lt; 5 && x &lt; 10</td>
          </tr>
          <tr>
            <td class="tg-0lax">||</td>
            <td class="tg-0lax">
              Renvoie Vrai si l'une des déclarations est vraie.
            </td>
            <td class="tg-0lax">x &lt; 5 || x &lt; 4</td>
          </tr>
          <tr>
            <td class="tg-0lax">!</td>
            <td class="tg-0lax">
              Inverse le résultat, renvoie Faux si le résultat est vrai.
            </td>
            <td class="tg-0lax">!(x &lt; 5 && x &lt; 10)</td>
          </tr>
        </tbody>
      </table>
      <img
        src="../assets/illustrations/andornot.svg"
        style="width: 58%; margin-top: 1%"
      />
    </div>
  </div>
</template>

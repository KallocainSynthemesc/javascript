<template>
  <div class="slide">
    <div class="heading">Data Types - Escape Sequences in String</div>
    <div class="content">
      <p>
        Le caractère backslash (\) a une fonction particulière dans les strings
        JavaScript. Combiné avec le caractère qui le suit, il représente un
        caractère qui n'est pas autrement représentable dans le string.
      </p>
      <div class="flex-container">
        <div>
          <table class="tg">
            <thead>
              <tr>
                <th class="tg-0pky">
                  <span style="font-weight: bold">Sequence</span>
                </th>
                <th class="tg-0pky">
                  <span style="font-weight: bold">Caractère représenté</span>
                </th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td class="tg-0pky">\0</td>
                <td class="tg-0pky">Le caractère NUL (\u0000)</td>
              </tr>
              <tr>
                <td class="tg-0pky">\b</td>
                <td class="tg-0pky">Retour en arrière (\u0008)</td>
              </tr>
              <tr>
                <td class="tg-0pky">\t</td>
                <td class="tg-0pky">Horizontal tab (\u0009)</td>
              </tr>
              <tr>
                <td class="tg-0pky">\n</td>
                <td class="tg-0pky">Nouvelle ligne(\u000A)</td>
              </tr>
              <tr>
                <td class="tg-0pky">\v</td>
                <td class="tg-0pky">Onglet vertical(\u000B)</td>
              </tr>
              <tr>
                <td class="tg-0pky">\f</td>
                <td class="tg-0pky">Form feed (\u000C)</td>
              </tr>
            </tbody>
          </table>
        </div>
        <div>
          <table class="tg">
            <thead>
              <tr>
                <th class="tg-0pky">
                  <span style="font-weight: bold">Sequence</span>
                </th>
                <th class="tg-0pky">
                  <span style="font-weight: bold">Caractère représenté</span>
                </th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td class="tg-0pky">\r</td>
                <td class="tg-0pky">Retour à la ligne (\u000D)</td>
              </tr>
              <tr>
                <td class="tg-0pky">\"</td>
                <td class="tg-0pky">Guillemets doubles (\u0022)</td>
              </tr>
              <tr>
                <td class="tg-0pky">\'</td>
                <td class="tg-0pky">
                  Apostrophe ou Guillemets simples (\u0027
                </td>
              </tr>
              <tr>
                <td class="tg-0pky">\\</td>
                <td class="tg-0pky">Backslash (\u005C)</td>
              </tr>
              <tr>
                <td class="tg-0pky">\x XX</td>
                <td class="tg-0pky">
                  Le caractère Latin-1 spécifié par les deux chiffres
                  hexadécimaux XX
                </td>
              </tr>
              <tr>
                <td class="tg-0pky">\u XXXX</td>
                <td class="tg-0pky">
                  Le caractère Unicode spécifié par les quatre chiffres
                  hexadécimaux XXXX
                </td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </div>
  </div>
</template>

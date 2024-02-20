<template>
  <div class="slide">
    <div class="heading">Opérateurs logiques - !</div>
    <div class="content">
      <p>
        L'opérateur <b>not</b> s'applique à une seule condition. Et il inverse
        le résultat de cette condition, <b>True</b> devient <b>False</b> et
        <b>False</b> devient <b>True</b>.
      </p>
      <table class="tg" style="width: 30%; height: 50%">
        <thead>
          <tr>
            <th class="tg-0lax"><span style="font-weight: bold">a</span></th>
            <th class="tg-0lax"><span style="font-weight: bold">! a</span></th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="tg-0lax" style="color: #008000">True</td>
            <td class="tg-0lax" style="color: #800400">False</td>
          </tr>
          <tr>
            <td class="tg-0lax" style="color: #800400">False</td>
            <td class="tg-0lax" style="color: #008000">True</td>
          </tr>
        </tbody>
      </table>
      <br />
      <div
        style="
          background: #ffffff;
          overflow: auto;
          width: auto;
          border: solid gray;
          border-width: 0.1em 0.1em 0.1em 0.8em;
          padding: 0.2em 0.6em;
          width: 30%;
        "
      >
        <pre style="margin: 0; line-height: 125%">
                  console.log(!<span style="color: #000080; font-weight: bold">true</span>) <span style="color: #008800; font-style: italic">//False</span>
                  console.log(!<span style="color: #000080; font-weight: bold">false</span>) <span style="color: #008800; font-style: italic">//True</span></pre>
      </div>

      <img
        src="../assets/illustrations/uno-reverse.svg"
        class="html-css-logo"
        style="left: 40%; top: 30%; height: 66%; width: unset"
      />
    </div>
  </div>
</template>

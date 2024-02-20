<template>
  <div class="slide">
    <div class="heading">Opérateurs logiques - &&</div>
    <div class="content">
      <p>
        Elle donne <b>True</b> si les <b>deux conditions</b> sont <b>True</b>.
        Et elle donne <b>False</b> si <b>l'une ou l'autre</b> des conditions a
        ou b est <b>False</b>.
      </p>
      <table class="tg" style="width: 100%; height: 50%">
        <thead>
          <tr>
            <th class="tg-0lax"><span style="font-weight: bold">a</span></th>
            <th class="tg-0lax"><span style="font-weight: bold">b</span></th>
            <th class="tg-0lax">
              <span style="font-weight: bold">a && b</span>
            </th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="tg-0lax" style="color: #008000">True</td>
            <td class="tg-0lax" style="color: #008000">True</td>
            <td class="tg-0lax" style="color: #008000">True</td>
          </tr>
          <tr>
            <td class="tg-0lax" style="color: #008000">True</td>
            <td class="tg-0lax" style="color: #800400">False</td>
            <td class="tg-0lax" style="color: #800400">False</td>
          </tr>
          <tr>
            <td class="tg-0lax" style="color: #800400">False</td>
            <td class="tg-0lax" style="color: #800400">False</td>
            <td class="tg-0lax" style="color: #800400">False</td>
          </tr>
          <tr>
            <td class="tg-0lax" style="color: #800400">False</td>
            <td class="tg-0lax" style="color: #008000">True</td>
            <td class="tg-0lax" style="color: #800400">False</td>
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
        "
      >
        <pre style="margin: 0; line-height: 125%">
                  console.log(<span style="color: #000080; font-weight: bold">true</span> &amp;&amp; <span style="color: #000080; font-weight: bold">true</span>) <span style="color: #008800; font-style: italic">//True</span>
                  console.log(<span style="color: #000080; font-weight: bold">true</span> &amp;&amp; <span style="color: #000080; font-weight: bold">false</span>) <span style="color: #008800; font-style: italic">//False</span>
                  console.log(<span style="color: #000080; font-weight: bold">false</span> &amp;&amp; <span style="color: #000080; font-weight: bold">false</span>) <span style="color: #008800; font-style: italic">//False</span>
                  console.log(<span style="color: #000080; font-weight: bold">false</span> &amp;&amp; <span style="color: #000080; font-weight: bold">true</span>) <span style="color: #008800; font-style: italic">//False</span></pre>
      </div>
    </div>
  </div>
</template>

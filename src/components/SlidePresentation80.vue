<template>
  <div class="slide">
    <div class="heading">Prédominance des opérateurs logiques</div>
    <div class="content">
      <table class="tg" style="height: 50%">
        <tbody>
          <tr>
            <td class="tg-0lax">a || b && c</td>
            <td class="tg-0lax">signifie</td>
            <td class="tg-0lax">a || (b && c)</td>
          </tr>
          <tr>
            <td class="tg-0lax">a && b || c && d</td>
            <td class="tg-0lax">signifie</td>
            <td class="tg-0lax">(a && b) || (c && d)</td>
          </tr>
          <tr>
            <td class="tg-0lax">a && b && c || d</td>
            <td class="tg-0lax">signifie</td>
            <td class="tg-0lax">((a && b) && c) || d</td>
          </tr>
          <tr>
            <td class="tg-0lax">! a && b || c</td>
            <td class="tg-0lax">signifie</td>
            <td class="tg-0lax">((! a) && b) || c</td>
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
                  <span style="color: #000080; font-weight: bold">let</span> a = <span style="color: #000080; font-weight: bold">true</span>;
                  <span style="color: #000080; font-weight: bold">let</span> b = <span style="color: #000080; font-weight: bold">false</span>;
                  <span style="color: #000080; font-weight: bold">let</span> c = <span style="color: #000080; font-weight: bold">true</span>;

                  console.log(a || b &amp;&amp; c) <span style="color: #008800; font-style: italic">//True</span>
                  console.log(a || (b &amp;&amp; c)) <span style="color: #008800; font-style: italic">//True (même instruction que ci-dessus)</span>
                  console.log(! a &amp;&amp; b || c) <span style="color: #008800; font-style: italic">//True</span>
                  console.log(((! a) &amp;&amp; b) || c) <span style="color: #008800; font-style: italic">//True (même instruction que ci-dessus)</span></pre>
      </div>
    </div>
  </div>
</template>

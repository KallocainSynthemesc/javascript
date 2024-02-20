<template>
  <div class="slide">
    <div class="heading">Callback</div>
    <div class="content">
      <p>
        Un callback est une fonction passée comme argument à une autre fonction.
      </p>
      <p>Exemple:</p>
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
                  <span style="color: #008800; font-weight: bold">function</span> displayer(value) {
                    console.log(value)
                  }

                  <span style="color: #008800; font-weight: bold">function</span> calculator(num1, num2, callbackFunc) {
                    <span style="color: #008800; font-weight: bold">let</span> sum <span style="color: #333333">=</span> num1 <span style="color: #333333">+</span> num2;
                    callbackFunc(sum);
                  }

                  calculator(<span style="color: #0000DD; font-weight: bold">5</span>, <span style="color: #0000DD; font-weight: bold">5</span>, displayer);</pre>
      </div>
    </div>
  </div>
</template>

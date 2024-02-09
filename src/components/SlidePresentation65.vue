<template>
  <div class="slide">
    <div class="heading">Functions - Argument-Passing Basics</div>
    <div class="content">
      <div class="flex-container">
        <div style="width: 64%">
          <p>
            <b
              >La modification de l'argument d'un objet mutable dans une
              fonction peut avoir un impact sur l'appelant.</b
            >
          </p>
          <p>
            <b>Exemple :</b>
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
                      arr = [<span style="color: #009999">1</span>,<span style="color: #009999">2</span>,<span style="color: #009999">3</span>,<span style="color: #009999">4</span>];
                      <span style="color: #0000aa">function</span> mutate(arr){
                        arr[<span style="color: #009999">0</span>] = <span style="color: #009999">100</span>
                      }
                      mutate(arr);
                      console.log(arr[<span style="color: #009999">0</span>]);</pre>
          </div>
        </div>
        <div style="width: 52%">
          <img src="../assets/illustrations/mutable.svg" style="width: 100%" />
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
                      arr = [<span style="color: #009999">1</span>,<span style="color: #009999">2</span>,<span style="color: #009999">3</span>,<span style="color: #009999">4</span>];
                      <span style="color: #0000aa">function</span> mutate(arr){
                        arr = [<span style="color: #009999">100</span>,<span style="color: #009999">200</span>,<span style="color: #009999">300</span>,<span style="color: #009999">400</span>]
                      }
                      mutate(arr);
                      console.log(arr[<span style="color: #009999">0</span>]);</pre>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

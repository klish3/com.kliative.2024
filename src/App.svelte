<!-- <script lang="ts">

</script> -->

<main>
  <style>
 
  </style>
  
  
  
  <div class="wakandaforever" title="kliative.com">
      <div class="wakandaforever" title="kliative.com"></div>
      kliative.com
  <div class="wakandaforever" title="kliative.com"></div>
  </div>
  
</main>

<style>
 /*  fonts */
 @font-face {
      font-family: BEYNO;
      src: url(./assets/fonts/BEYNO.otf);
    }
  
    @font-face {
      font-family: wakandaforever;
      src: url(./assets/fonts/wakandaforever.otf);
    }
  
    body {
      display: flex;
      width: 100vw;
      height: 100vh;
      align-items: center;
      justify-content: center;
      margin: 0;
      background: #131313;
      color: #fff;
      font-size: 50px;
      letter-spacing: -7px;
    }
  
  
    .wakandaforever{
       font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
       font-weight: 100;
       letter-spacing: 0.7rem;
       font-size: 3rem;
    }
  
    .benyo {
      font-family: BEYNO;
    }
  
  
    div {
      animation: glitch 1s linear infinite;
    }
  
    @keyframes glitch {
  
      2%,
      64% {
        transform: translate(2px, 0) skew(0deg);
      }
  
      4%,
      60% {
        transform: translate(-2px, 0) skew(0deg);
      }
  
      62% {
        transform: translate(0, 0) skew(5deg);
      }
    }
  
    div:before,
    div:after {
      content: attr(title);
      position: absolute;
      left: 0;
    }
  
    div:before {
      animation: glitchTop 1s linear infinite;
      clip-path: polygon(0 0, 100% 0, 100% 33%, 0 33%);
      -webkit-clip-path: polygon(0 0, 100% 0, 100% 33%, 0 33%);
    }
  
    @keyframes glitchTop {
  
      2%,
      64% {
        transform: translate(2px, -2px);
         font-family: wakandaforever;
         color: gray;
      }
  
      4%,
      60% {
        transform: translate(-2px, 2px);
         font-family: wakandaforever;
         color: gray;
      }
  
      62% {
        transform: translate(13px, -1px) skew(-13deg);
         font-family: wakandaforever;
         color: gray;
      }
    }
  
    div:after {
      animation: glitchBotom 1.5s linear infinite;
      clip-path: polygon(0 67%, 100% 67%, 100% 100%, 0 100%);
      -webkit-clip-path: polygon(0 67%, 100% 67%, 100% 100%, 0 100%);
    }
  
    @keyframes glitchBotom {
  
      2%,
      64% {
        transform: translate(-2px, 0);
        font-family: wakandaforever;
        color: gray;
      }
  
      4%,
      60% {
        transform: translate(-2px, 0);
        font-family: wakandaforever;
        color: gray;
      }
  
      62% {
        transform: translate(-22px, 5px) skew(21deg);
        font-family: wakandaforever;
        color:dark-gray;
      }
    }
  

    /* fonts */
    @font-face {
      font-family: BEYNO;
      src: url(BEYNO.otf);
    }
  
    @font-face {
      font-family: wakandaforever;
      src: url(wakandaforever.otf);
    }
  
    body {
      display: flex;
      width: 100vw;
      height: 100vh;
      align-items: center;
      justify-content: center;
      margin: 0;
      background: #131313;
      color: #fff;
      font-size: 50px;
      letter-spacing: -7px;
    }
  
    .wakandaforever {
      font-family: BEYNO;
    }
  
    .glitch-text {
      font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
      font-weight: 100;
      letter-spacing: 0.7rem;
      font-size: 3rem;
      animation: glitch 1s linear infinite;
    }
  
    @keyframes glitch {
  
      2%,
      64% {
        transform: translate(2px, 0) skew(0deg);
      }
  
      4%,
      60% {
        transform: translate(-2px, 0) skew(0deg);
      }
  
      62% {
        transform: translate(0, 0) skew(5deg);
      }
  
      div:nth-child(1) { /* Top half */
        clip-path: polygon(0 0, 100% 0, 100% 33%, 0 33%);
        -webkit-clip-path: polygon(0 0, 100% 0, 100% 33%, 0 33%);
        animation-timing-function: steps(2, ease-in-out); /* Adjust for stutter effect */
        color: gray;
      }
  
      div:nth-child(2) { /* Bottom half */
        clip-path: polygon(0 67%, 100% 67%, 100% 100%, 0 100%);
        -webkit-clip-path: polygon(0 67%, 100% 67%, 100% 100%, 0 100%);
        animation-timing-function: steps(4, ease-in-out); /* Adjust for stutter effect (more stutter) */
        color: dark-gray;
      }
    }
</style>

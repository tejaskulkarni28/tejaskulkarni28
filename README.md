![Bottom_Down_Wave](https://github.com/user-attachments/assets/1e9cbd7b-45ef-4c78-b7d6-8b4c4e240ab2)
![Uploading Bottom_Down_Wave.s<svg viewBox="0 0 120 20" xmlns="http://www.w3.org/2000/svg"
  xmlns:xlink="http://www.w3.org/1999/xlink">

  <!-- CSS -->
  <style>
  svg {
    width: 100vw;
    position: fixed;
    top: 5px;
    transform: rotate(360deg);
    overflow: visible;
    }

    <!-- Last Wave -->
    .wave {
        animation: wave 2s linear;
        animation-iteration-count: infinite;
        opacity: 0.6;
        fill: #01AAff;
        }

    #wave2 {
        animation-duration: 9s;
        animation-direction: reverse;
        opacity: 0.07;
        fill: #01AAFF;
        }

    #wave3 {
        animation-duration: 8s;
        opacity: 0.08;
        fill: #01AAFF;
    }

    #wave4 {
        animation-duration: 7s;
        animation-direction: reverse;
        opacity: 0.09;
        fill: #01AAFF;
    }

    #wave5 {
        animation-duration: 6s;
        opacity: 0.10;
        fill: #01AAFF;
        }

    #wave6 {
        animation-duration: 5s;
        animation-direction: reverse;
        opacity: 0.09;
        fill: #01AAFF;
        }

    #wave7 {
        animation-duration: 4s;
        opacity: 0.08;
        fill: #01AAFF;
        }

    #wave8 {
        animation-duration: 3s;
        animation-direction: reverse;
        opacity: 0.07;
        fill: #01AAFF;
        }

    <!-- First Wave -->
    #wave9 {
        animation-duration: 2s;
        opacity: 0.06;
        fill: #01AAFF;
    }

    @keyframes wave { to { transform: translateX(-100%); } }

    </style>

  <defs>
    <filter id="anim">
      <feGaussianBlur in="SourceGraphic" stdDeviation="1" result="blur" />
      <feColorMatrix in="blur" mode="matrix"
        values="
           1 0 0 0 0
           0 1 0 0 0
           0 0 1 0 0
           0 0 0 1 0"
        result="anim" />
      <xfeBlend in="SourceGraphic" in2="anim" />
    </filter>

    <path id="wave"
      d="M 0,10 C 30,10 30,15 60,15 90,15 90,10 120,10 150,10 150,15 180,15 210,15 210,10 240,10 v 28 h -240 z" />
  </defs>

  <use id="wave2" class="wave" xlink:href="#wave" x="0" y="0"></use>
  <use id="wave3" class="wave" xlink:href="#wave" x="0" y="-1"></use>
  <use id="wave4" class="wave" xlink:href="#wave" x="0" y="-2"></use>
  <use id="wave5" class="wave" xlink:href="#wave" x="0" y="-3"></use>
  <use id="wave6" class="wave" xlink:href="#wave" x="0" y="-4"></use>
  <use id="wave7" class="wave" xlink:href="#wave" x="0" y="-5"></use>
  <use id="wave8" class="wave" xlink:href="#wave" x="0" y="-6"></use>
  <use id="wave9" class="wave" xlink:href="#wave" x="0" y="-7"></use>
</svg>
vg…]()

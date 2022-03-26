<template>
  <div class="body">
    <div class="section">
      <div class="leaf">
        <div>
          <img
            src="http://www.pngmart.com/files/1/Fall-Autumn-Leaves-Transparent-PNG.png"
            height="75px"
            width="75px"
          />
        </div>
        <div>
          <img
            src="http://www.pngmart.com/files/1/Autumn-Fall-Leaves-Pictures-Collage-PNG.png"
            height="75px"
            width="75px"
          />
        </div>
        <div>
          <img
            src="http://www.pngmart.com/files/1/Autumn-Fall-Leaves-Clip-Art-PNG.png"
            height="75px"
            width="75px"
          />
        </div>
        <div>
          <img
            src="http://www.pngmart.com/files/1/Green-Leaves-PNG-File.png"
            height="75px"
            width="75px"
          />
        </div>
        <div>
          <img
            src="http://www.pngmart.com/files/1/Transparent-Autumn-Leaves-Falling-PNG.png"
            height="75px"
            width="75px"
          />
        </div>
        <div>
          <img
            src="http://www.pngmart.com/files/1/Realistic-Autumn-Fall-Leaves-PNG.png"
            height="75px"
            width="75px"
          />
        </div>
        <div>
          <img
            src="http://cdn.clipart-db.ru/rastr/autumn_leaves_025.png"
            height="75px"
            width="75px"
          />
        </div>
      </div>
    </div>
  </div>

  <div class="grid grid-cols-2 gap-6">
    <div class="text-2xl space-y-9">
      <h1 class="text-4xl text-white">Discounts & Promotions</h1>
      <h2>
        • Sign up and get 15% off your next purchase.
        <h2>• Green Planet members get a 30% birthday discount.</h2>

        <h2>• Extra 20% off sitewide with this Green Planet coupon code •</h2>
        Unlock 10% student discount with Student Beans.
      </h2>
<button class="cta">
  <span>learn more</span>
  <svg viewBox="0 0 13 10" height="10px" width="15px">
    <path d="M1,5 L11,5"></path>
    <polyline points="8 1 12 5 8 9"></polyline>
  </svg>
</button>
    </div>
    <div class=" xl">
      <img src="../assets/15.png" alt="" srcset="" />
    </div>

  </div>
</template>
<style scoped>


.cta {
 position: relative;
 margin: auto;
 padding: 12px 18px;
 transition: all 0.2s ease;
 border: none;
 background: none;
}

.cta:before {
 content: "";
 position: absolute;
 top: 0;
 left: 0;
 display: block;
 border-radius: 50px;
 background: #b1dae7;
 width: 45px;
 height: 45px;
 transition: all 0.3s ease;
}

.cta span {
 position: relative;
 font-family: "Ubuntu", sans-serif;
 font-size: 25px;
 font-weight: 700;
 letter-spacing: 0.05em;
 color: #eef4fa;
}

.cta svg {
 position: relative;
 top: 0;
 margin-left: 10px;
 fill: none;
 stroke-linecap: round;
 stroke-linejoin: round;
 stroke: #234567;
 stroke-width: 2;
 transform: translateX(-5px);
 transition: all 0.3s ease;
}

.cta:hover:before {
 width: 100%;
 background: #b1dae7;
}

.cta:hover svg {
 transform: translateX(0);
}

.cta:active {
 transform: scale(0.95);
}
.xl{clip-path: polygon(25% 0%, 52% 15%, 76% 79%, 0 96%, 0 8%);
}
.leaf {
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
}
.leaf div {
  position: absolute;
}
.leaf div:nth-child(1) {
  left: 20%;
  animation: fall 15s linear infinite;
  animation-delay: -2s;
}
.leaf div:nth-child(2) {
  left: 70%;
  animation: fall 15s linear infinite;
  animation-delay: -4s;
}
.leaf div:nth-child(3) {
  left: 10%;
  animation: fall 20s linear infinite;
  animation-delay: -7s;
}
.leaf div:nth-child(4) {
  left: 50%;
  animation: fall 18s linear infinite;
  animation-delay: -5s;
}
.leaf div:nth-child(5) {
  left: 85%;
  animation: fall 14s linear infinite;
  animation-delay: -5s;
}
.leaf div:nth-child(6) {
  left: 15%;
  animation: fall 16s linear infinite;
  animation-delay: -10s;
}
.leaf div:nth-child(7) {
  left: 90%;
  animation: fall 15s linear infinite;
  animation-delay: -4s;
}
@keyframes fall {
  0% {
    opacity: 1;
    top: -10%;
    transform: translateX (20px) rotate(0deg);
  }
  20% {
    opacity: 0.8;
    transform: translateX (-20px) rotate(45deg);
  }
  40% {
    transform: translateX (-20px) rotate(90deg);
  }
  60% {
    transform: translateX (-20px) rotate(135deg);
  }
  80% {
    transform: translateX (-20px) rotate(180deg);
  }
  100% {
    top: 110%;
    transform: translateX (-20px) rotate(225deg);
  }
}
.leaf1 {
  transform: rotateX(180deg);
}
</style>

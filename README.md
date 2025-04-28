# skorikov.github.io

Сайт-визитка настоящего художника.
Скориков Игорь Андреевич.
Член Союза Художников России.


<style>
  body {
    margin: 0;
    padding: 0;
    font-family: 'Arial', sans-serif;
    background-color: #f5f5f5;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
  }

  .business-card {
    width: 800px;
    max-width: 100%;
    height: 450px;
    background-color: #000;
    display: flex;
    overflow: hidden;
    box-shadow: 0 10px 20px rgba(0,0,0,0.3);
    margin: 20px auto;
  }

  @media (max-width: 800px) {
    .business-card {
      flex-direction: column;
      height: auto;
    }
    .left-side, .right-side {
      width: 100% !important;
    }
    .left-side {
      height: 200px !important;
    }
  }

  .left-side {
    width: 50%;
    height: 100%;
    position: relative;
    overflow: hidden;
  }

  .right-side {
    width: 50%;
    height: 100%;
    padding: 40px;
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    color: #FFCC00;
  }

  .qr-code {
    width: 180px;
    height: 180px;
    background-color: #FFCC00;
    margin-bottom: 10px;
  }

  .name {
    font-size: 24px;
    font-weight: bold;
    letter-spacing: 1px;
    margin: 15px 0;
  }

  .divider {
    width: 100%;
    height: 2px;
    background-color: #FFCC00;
    margin: 10px 0;
  }

  .short-divider {
    width: 70%;
    height: 2px;
    background-color: #FFCC00;
    margin: 5px 0;
  }

  .contact-info {
    text-align: center;
    margin: 10px 0;
  }

  .contact-info div {
    margin: 8px 0;
  }

  .decorative-element {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
  }

  .decorative-element::before,
  .decorative-element::after {
    content: "";
    height: 1px;
    background-color: #FFCC00;
    flex-grow: 1;
  }

  .decorative-element .symbol {
    margin: 0 10px;
    font-size: 20px;
    color: #FFCC00;
  }
</style>
<div class="business-card">
  <div class="left-side">
    <svg class="swirl" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg" style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); width: 80%; height: 80%;">
      <path d="M100,30 C130,30 160,60 160,100 C160,140 130,170 90,170 C50,170 30,140 30,100 C30,60 70,100 100,100 C130,100 130,60 100,30 Z"
            fill="none"
            stroke="#FFCC00"
            stroke-width="15"
            stroke-linecap="round"
            stroke-linejoin="round">
        <animate attributeName="d"
                 dur="3s"
                 repeatCount="indefinite"
                 values="M100,30 C130,30 160,60 160,100 C160,140 130,170 90,170 C50,170 30,140 30,100 C30,60 70,100 100,100 C130,100 130,60 100,30 Z;
                         M100,40 C140,40 150,70 150,100 C150,130 130,160 90,160 C60,160 40,130 40,100 C40,70 60,110 100,110 C140,110 140,70 100,40 Z;
                         M100,30 C130,30 160,60 160,100 C160,140 130,170 90,170 C50,170 30,140 30,100 C30,60 70,100 100,100 C130,100 130,60 100,30 Z"
                 calcMode="spline"
                 keySplines="0.4 0 0.6 1; 0.4 0 0.6 1">
        </animate>
      </path>
    </svg>
  </div>
  <div class="right-side">
    <div class="decorative-element">
      <span class="symbol">⟁</span>
    </div>
<div class="qr-code">
  <!-- QR code for Igor Skorikov -->
  <svg viewBox="0 0 29 29" fill="none" xmlns="http://www.w3.org/2000/svg" width="100%" height="100%">
    <!-- QR Code Pattern -->
    <rect width="29" height="29" fill="#FFCC00"/>
    <!-- QR code squares - simplified representation -->
    <rect x="2" y="2" width="3" height="3" fill="black"/>
    <rect x="5" y="2" width="3" height="3" fill="black"/>
    <rect x="8" y="2" width="3" height="3" fill="black"/>
    <rect x="2" y="5" width="3" height="3" fill="black"/>
    <rect x="8" y="5" width="3" height="3" fill="black"/>
    <rect x="2" y="8" width="3" height="3" fill="black"/>
    <rect x="5" y="8" width="3" height="3" fill="black"/>
    <rect x="8" y="8" width="3" height="3" fill="black"/>

    <rect x="18" y="2" width="3" height="3" fill="black"/>
    <rect x="21" y="2" width="3" height="3" fill="black"/>
    <rect x="24" y="2" width="3" height="3" fill="black"/>
    <rect x="18" y="5" width="3" height="3" fill="black"/>
    <rect x="24" y="5" width="3" height="3" fill="black"/>
    <rect x="18" y="8" width="3" height="3" fill="black"/>
    <rect x="21" y="8" width="3" height="3" fill="black"/>
    <rect x="24" y="8" width="3" height="3" fill="black"/>

    <rect x="2" y="18" width="3" height="3" fill="black"/>
    <rect x="5" y="18" width="3" height="3" fill="black"/>
    <rect x="8" y="18" width="3" height="3" fill="black"/>
    <rect x="2" y="21" width="3" height="3" fill="black"/>
    <rect x="8" y="21" width="3" height="3" fill="black"/>
    <rect x="2" y="24" width="3" height="3" fill="black"/>
    <rect x="5" y="24" width="3" height="3" fill="black"/>
    <rect x="8" y="24" width="3" height="3" fill="black"/>

    <!-- Additional QR patterns -->
    <rect x="12" y="4" width="1" height="1" fill="black"/>
    <rect x="14" y="6" width="1" height="1" fill="black"/>
    <rect x="13" y="9" width="1" height="1" fill="black"/>
    <rect x="15" y="12" width="1" height="1" fill="black"/>
    <rect x="12" y="15" width="1" height="1" fill="black"/>
    <rect x="15" y="17" width="1" height="1" fill="black"/>
    <rect x="14" y="20" width="1" height="1" fill="black"/>
    <rect x="17" y="24" width="1" height="1" fill="black"/>
    <rect x="20" y="17" width="1" height="1" fill="black"/>
    <rect x="22" y="19" width="1" height="1" fill="black"/>
    <rect x="19" y="22" width="1" height="1" fill="black"/>
    <rect x="24" y="15" width="1" height="1" fill="black"/>
    <rect x="22" y="13" width="1" height="1" fill="black"/>
  </svg>
</div>

<div class="name">IGOR SKORIKOV</div>

<div class="divider"></div>
<div class="short-divider"></div>

<div class="contact-info">
  <div>+7(952)955 22 67</div>
  <div>tg: @Igor_Skorikov</div>
  <div>skorikov.igor@gmail.com</div>
  <div>vk.com/igorandreev12345</div>
</div>

<div class="decorative-element">
  <span class="symbol">⥊</span>
</div>
  </div>
</div>
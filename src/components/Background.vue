<template>
  <!-- Floating background blocks for playful effect -->
  <div class="floating-bg">
    <div class="float-block block1"></div>
    <div class="float-block block2"></div>
    <div class="float-block block3"></div>
    <div class="float-block block4"></div>
    <div class="float-block block5"></div>
    <div class="float-block block6"></div>
    <div class="float-block block7"></div>
    <div class="float-block block8"></div>
    <div class="float-block block9"></div>
    <div class="float-block block10"></div>
    <div class="float-block block11"></div>
    <div class="float-block block12"></div>
    <div class="float-block block13"></div>
    <div class="float-block block14"></div>
    <div class="float-block block15"></div>
    <div class="float-block block16"></div>
    <div class="float-block block17"></div>
    <div class="float-block block18"></div>
    <div class="float-block block19"></div>
    <div class="float-block block20"></div>
    <div class="float-block block21"></div>
    <div class="float-block block22"></div>
    <div class="float-block block23"></div>
    <div class="float-block block24"></div>
    <div class="float-block block25"></div>
    <div class="float-block block26"></div>
    <div class="float-block block27"></div>
    <div class="float-block block28"></div>
    <div class="float-block block29"></div>
    <div class="float-block block30"></div>
    <div class="float-block block31"></div>
    <div class="float-block block32"></div>
    <div class="float-block block33"></div>
    <div class="float-block block12"></div>
    <div class="float-block block13"></div>
    <div class="float-block block14"></div>
    <div class="float-block block15"></div>
    <div class="float-block block16"></div>
    <div class="float-block block17"></div>
    <div class="float-block block18"></div>
    <div class="float-block block19"></div>
    <div class="float-block block20"></div>
    <div class="float-block block21"></div>
    <div class="float-block block22"></div>
    <div class="float-block block23"></div>
    <div class="float-block block24"></div>
    <div class="float-block block25"></div>
    <div class="float-block block26"></div>
    <div class="float-block block27"></div>
    <div class="float-block block28"></div>
    <div class="float-block block29"></div>
    <div class="float-block block30"></div>
    <div class="float-block block31"></div>
    <div class="float-block block32"></div>
    <div class="float-block block33"></div>
    <div class="float-block block34"></div>
    <div class="float-block block35"></div>
    <div class="float-block block36"></div>
    <div class="float-block block37"></div>
    <div class="float-block block38"></div>
    <div class="float-block block39"></div>
    <div class="float-block block40"></div>
    <div class="float-block block41"></div>
    <div class="float-block block42"></div>
    <div class="float-block block43"></div>
    <div class="float-block block44"></div>
    <div class="float-block block45"></div>
    <div class="float-block block46"></div>
    <div class="float-block block47"></div>
    <div class="float-block block48"></div>
    <div class="float-block block49"></div>
    <div class="float-block block50"></div>
    <div class="float-block block51"></div>
    <div class="float-block block52"></div>
    <div class="float-block block53"></div>
    <div class="float-block block54"></div>
    <div class="float-block block55"></div>
    <div class="float-block block56"></div>
    <div class="float-block block57"></div>
    <div class="float-block block58"></div>
    <div class="float-block block59"></div>
    <div class="float-block block60"></div>
    <div class="float-block block61"></div>
    <div class="float-block block62"></div>
    <div class="float-block block63"></div>
    <div class="float-block block64"></div>
    <div class="float-block block65"></div>
    <div class="float-block block66"></div>
    <div class="float-block block67"></div>
    <div class="float-block block68"></div>
    <div class="float-block block69"></div>
    <div class="float-block block70"></div>
    <div class="float-block block71"></div>
    <div class="float-block block72"></div>
    <div class="float-block block73"></div>
    <div class="float-block block74"></div>
    <div class="float-block block75"></div>
    <div class="float-block block76"></div>
    <div class="float-block block77"></div>
    <div class="float-block block78"></div>
    <div class="float-block block79"></div>
    <div class="float-block block80"></div>
  </div>
</template>
<style scoped>
.floating-bg {
  position: fixed;
  inset: 0;
  z-index: 0;
  pointer-events: none;
  overflow: hidden;
}
.float-block {
  position: absolute;
  border-radius: 18px;
  opacity: 0.18;
  filter: blur(8px);
  animation: float 1s ease-in-out infinite alternate;
}
/* Individual floating block positions, colors, and delays */
.block1 {
  width: 180px;
  height: 180px;
  background: #6c63ff;
  top: 8%;
  left: 10%;
  animation-delay: 0s;
}
.block2 {
  width: 120px;
  height: 120px;
  background: #ff8c00;
  bottom: 12%;
  right: 14%;
  animation-delay: 2s;
}
.block3 {
  width: 90px;
  height: 90px;
  background: #42b883;
  top: 60%;
  left: 70%;
  animation-delay: 4s;
}
.block4 {
  width: 100px;
  height: 100px;
  background: #00bcd4;
  top: 20%;
  right: 20%;
  animation-delay: 1s;
}
.block5 {
  width: 70px;
  height: 70px;
  background: #ff5ca7;
  bottom: 30%;
  left: 25%;
  animation-delay: 3s;
}
.block6 {
  width: 110px;
  height: 110px;
  background: #ffd600;
  top: 40%;
  left: 5%;
  animation-delay: 2.5s;
}
.block7 {
  width: 80px;
  height: 80px;
  background: #8e44ad;
  bottom: 18%;
  right: 30%;
  animation-delay: 5s;
}
.block8 {
  width: 60px;
  height: 60px;
  background: #00e676;
  top: 75%;
  left: 15%;
  animation-delay: 6s;
}
.block9 {
  width: 130px;
  height: 130px;
  background: #e17055;
  top: 10%;
  right: 40%;
  animation-delay: 3.5s;
}
.block10 {
  width: 90px;
  height: 90px;
  background: #00bfae;
  bottom: 8%;
  left: 60%;
  animation-delay: 7s;
}
.block11 {
  width: 75px;
  height: 75px;
  background: #f50057;
  top: 50%;
  right: 10%;
  animation-delay: 4.5s;
}
.block12 {
  width: 60px;
  height: 60px;
  background: #ffb300;
  bottom: 40%;
  left: 80%;
  animation-delay: 8s;
}
.block13 {
  width: 100px;
  height: 100px;
  background: #3949ab;
  top: 30%;
  right: 50%;
  animation-delay: 9s;
}
.block14 {
  width: 60px;
  height: 60px;
  background: #ff1744;
  top: 15%;
  left: 60%;
  animation-delay: 2.2s;
}
.block15 {
  width: 80px;
  height: 80px;
  background: #00bcd4;
  bottom: 10%;
  right: 5%;
  animation-delay: 3.7s;
}
.block16 {
  width: 50px;
  height: 50px;
  background: #ffd600;
  top: 80%;
  left: 40%;
  animation-delay: 5.1s;
}
.block17 {
  width: 100px;
  height: 100px;
  background: #ab47bc;
  top: 25%;
  right: 35%;
  animation-delay: 6.3s;
}
.block18 {
  width: 70px;
  height: 70px;
  background: #00e676;
  bottom: 18%;
  right: 10%;
  animation-delay: 7.5s;
}
.block19 {
  width: 90px;
  height: 90px;
  background: #ff9100;
  top: 55%;
  right: 15%;
  animation-delay: 8.2s;
}
.block20 {
  width: 65px;
  height: 65px;
  background: #2979ff;
  bottom: 25%;
  left: 55%;
  animation-delay: 9.1s;
}
.block21 {
  width: 85px;
  height: 85px;
  background: #c51162;
  top: 35%;
  right: 80%;
  animation-delay: 10.4s;
}
.block22 {
  width: 55px;
  height: 55px;
  background: #00c853;
  bottom: 60%;
  left: 25%;
  animation-delay: 11.2s;
}
.block23 {
  width: 75px;
  height: 75px;
  background: #ffea00;
  top: 65%;
  right: 30%;
  animation-delay: 12s;
}
.block24 {
  width: 55px;
  height: 55px;
  background: #ff80ab;
  top: 22%;
  left: 35%;
  animation-delay: 13s;
}
.block25 {
  width: 70px;
  height: 70px;
  background: #00bcd4;
  bottom: 12%;
  left: 75%;
  animation-delay: 13.5s;
}
.block26 {
  width: 60px;
  height: 60px;
  background: #ffd740;
  top: 38%;
  right: 12%;
  animation-delay: 14s;
}
.block27 {
  width: 90px;
  height: 90px;
  background: #b388ff;
  bottom: 45%;
  left: 18%;
  animation-delay: 14.5s;
}
.block28 {
  width: 80px;
  height: 80px;
  background: #ff5252;
  top: 70%;
  right: 28%;
  animation-delay: 15s;
}
.block29 {
  width: 65px;
  height: 65px;
  background: #69f0ae;
  bottom: 60%;
  right: 60%;
  animation-delay: 15.5s;
}
.block30 {
  width: 75px;
  height: 75px;
  background: #ffd600;
  top: 18%;
  right: 55%;
  animation-delay: 16s;
}
.block31 {
  width: 50px;
  height: 50px;
  background: #536dfe;
  bottom: 15%;
  right: 20%;
  animation-delay: 16.5s;
}
.block32 {
  width: 85px;
  height: 180px;
  background: #ffab00;
  top: 48%;
  left: 85%;
  animation-delay: 17s;
}
.block33 {
  width: 60px;
  height: 60px;
  background: #00e5ff;
  bottom: 35%;
  right: 40%;
  animation-delay: 17.5s;
}
.block34 {
  width: 70px;
  height: 70px;
  background: #ffb74d;
  top: 12%;
  left: 80%;
  animation-delay: 18s;
}
.block35 {
  width: 60px;
  height: 60px;
  background: #00bcd4;
  bottom: 20%;
  right: 10%;
  animation-delay: 18.5s;
}
.block36 {
  width: 90px;
  height: 90px;
  background: #d500f9;
  top: 45%;
  left: 60%;
  animation-delay: 19s;
}
.block37 {
  width: 80px;
  height: 80px;
  background: #76ff03;
  bottom: 50%;
  right: 25%;
  animation-delay: 19.5s;
}
.block38 {
  width: 55px;
  height: 55px;
  background: #ff4081;
  top: 78%;
  right: 10%;
  animation-delay: 20s;
}
.block39 {
  width: 100px;
  height: 100px;
  background: #00e676;
  bottom: 5%;
  left: 35%;
  animation-delay: 20.5s;
}
.block40 {
  width: 65px;
  height: 65px;
  background: #ff1744;
  top: 60%;
  right: 60%;
  animation-delay: 21s;
}
.block41 {
  width: 85px;
  height: 85px;
  background: #2979ff;
  bottom: 40%;
  left: 70%;
  animation-delay: 21.5s;
}
.block42 {
  width: 75px;
  height: 75px;
  background: #ffd600;
  top: 25%;
  right: 10%;
  animation-delay: 22s;
}
.block43 {
  width: 60px;
  height: 60px;
  background: #00bfae;
  bottom: 60%;
  right: 50%;
  animation-delay: 22.5s;
}
.block44 {
  width: 90px;
  height: 90px;
  background: #ffb300;
  top: 10%;
  left: 20%;
  animation-delay: 23s;
}
.block45 {
  width: 80px;
  height: 80px;
  background: #00e676;
  bottom: 15%;
  right: 60%;
  animation-delay: 23.5s;
}
.block46 {
  width: 70px;
  height: 70px;
  background: #ab47bc;
  top: 70%;
  left: 50%;
  animation-delay: 24s;
}
.block47 {
  width: 60px;
  height: 60px;
  background: #ff5252;
  bottom: 30%;
  right: 30%;
  animation-delay: 24.5s;
}
.block48 {
  width: 100px;
  height: 100px;
  background: #ffd600;
  top: 55%;
  left: 10%;
  animation-delay: 25s;
}
.block49 {
  width: 55px;
  height: 55px;
  background: #00bcd4;
  bottom: 45%;
  left: 80%;
  animation-delay: 25.5s;
}
.block50 {
  width: 85px;
  height: 85px;
  background: #ff80ab;
  top: 40%;
  right: 40%;
  animation-delay: 26s;
}
.block51 {
  width: 75px;
  height: 75px;
  background: #3949ab;
  bottom: 70%;
  left: 30%;
  animation-delay: 26.5s;
}
.block52 {
  width: 65px;
  height: 65px;
  background: #ffea00;
  top: 60%;
  right: 20%;
  animation-delay: 27s;
}
.block53 {
  width: 90px;
  height: 90px;
  background: #2979ff;
  bottom: 10%;
  left: 50%;
  animation-delay: 27.5s;
}
.block54 {
  width: 60px;
  height: 60px;
  background: #ff5ca7;
  top: 30%;
  left: 70%;
  animation-delay: 28s;
}
.block55 {
  width: 80px;
  height: 80px;
  background: #00c853;
  bottom: 20%;
  right: 40%;
  animation-delay: 28.5s;
}
.block56 {
  width: 50px;
  height: 50px;
  background: #ffb74d;
  top: 80%;
  left: 60%;
  animation-delay: 29s;
}
.block57 {
  width: 100px;
  height: 100px;
  background: #c51162;
  bottom: 60%;
  right: 15%;
  animation-delay: 29.5s;
}
.block58 {
  width: 70px;
  height: 70px;
  background: #ffd740;
  top: 35%;
  left: 40%;
  animation-delay: 30s;
}
.block59 {
  width: 60px;
  height: 60px;
  background: #00e5ff;
  bottom: 25%;
  right: 70%;
  animation-delay: 30.5s;
}
.block60 {
  width: 90px;
  height: 90px;
  background: #ff1744;
  top: 50%;
  left: 80%;
  animation-delay: 31s;
}
.block61 {
  width: 80px;
  height: 80px;
  background: #42b883;
  bottom: 40%;
  right: 60%;
  animation-delay: 31.5s;
}
.block62 {
  width: 75px;
  height: 75px;
  background: #ff9100;
  top: 20%;
  right: 30%;
  animation-delay: 32s;
}
.block63 {
  width: 65px;
  height: 65px;
  background: #536dfe;
  bottom: 60%;
  left: 20%;
  animation-delay: 32.5s;
}
.block34 {
  width: 70px;
  height: 70px;
  background: #ffb74d;
  top: 12%;
  right: 20%;
  animation-delay: 18s;
}
.block35 {
  width: 60px;
  height: 60px;
  background: #00bcd4;
  bottom: 20%;
  left: 10%;
  animation-delay: 18.5s;
}
.block36 {
  width: 90px;
  height: 90px;
  background: #d500f9;
  top: 45%;
  right: 60%;
  animation-delay: 19s;
}
.block37 {
  width: 80px;
  height: 80px;
  background: #76ff03;
  bottom: 50%;
  left: 25%;
  animation-delay: 19.5s;
}
.block38 {
  width: 55px;
  height: 55px;
  background: #ff4081;
  top: 78%;
  left: 10%;
  animation-delay: 20s;
}
.block39 {
  width: 100px;
  height: 100px;
  background: #00e676;
  bottom: 5%;
  right: 35%;
  animation-delay: 20.5s;
}
.block40 {
  width: 65px;
  height: 65px;
  background: #ff1744;
  top: 60%;
  left: 60%;
  animation-delay: 21s;
}
.block41 {
  width: 85px;
  height: 85px;
  background: #2979ff;
  bottom: 40%;
  right: 70%;
  animation-delay: 21.5s;
}
.block42 {
  width: 75px;
  height: 75px;
  background: #ffd600;
  top: 25%;
  left: 10%;
  animation-delay: 22s;
}
.block43 {
  width: 60px;
  height: 60px;
  background: #00bfae;
  bottom: 60%;
  left: 50%;
  animation-delay: 22.5s;
}
.block44 {
  width: 90px;
  height: 90px;
  background: #ffb300;
  top: 10%;
  right: 30%;
  animation-delay: 23s;
}
.block45 {
  width: 80px;
  height: 80px;
  background: #00e676;
  bottom: 15%;
  left: 60%;
  animation-delay: 23.5s;
}
.block46 {
  width: 70px;
  height: 70px;
  background: #ab47bc;
  top: 70%;
  right: 50%;
  animation-delay: 24s;
}
.block47 {
  width: 60px;
  height: 60px;
  background: #ff5252;
  bottom: 30%;
  left: 30%;
  animation-delay: 24.5s;
}
.block48 {
  width: 100px;
  height: 100px;
  background: #ffd600;
  top: 55%;
  right: 10%;
  animation-delay: 25s;
}
.block49 {
  width: 55px;
  height: 55px;
  background: #00bcd4;
  bottom: 45%;
  right: 80%;
  animation-delay: 25.5s;
}
.block50 {
  width: 85px;
  height: 85px;
  background: #ff80ab;
  top: 40%;
  left: 40%;
  animation-delay: 26s;
}
.block51 {
  width: 75px;
  height: 75px;
  background: #3949ab;
  bottom: 70%;
  right: 30%;
  animation-delay: 26.5s;
}
.block52 {
  width: 65px;
  height: 65px;
  background: #ffea00;
  top: 60%;
  left: 20%;
  animation-delay: 27s;
}
.block53 {
  width: 90px;
  height: 90px;
  background: #2979ff;
  bottom: 10%;
  right: 50%;
  animation-delay: 27.5s;
}
.block54 {
  width: 60px;
  height: 60px;
  background: #ff5ca7;
  top: 30%;
  right: 70%;
  animation-delay: 28s;
}
.block55 {
  width: 80px;
  height: 80px;
  background: #00c853;
  bottom: 20%;
  left: 40%;
  animation-delay: 28.5s;
}
.block56 {
  width: 50px;
  height: 50px;
  background: #ffb74d;
  top: 80%;
  right: 60%;
  animation-delay: 29s;
}
.block57 {
  width: 100px;
  height: 100px;
  background: #c51162;
  bottom: 60%;
  left: 15%;
  animation-delay: 29.5s;
}
.block58 {
  width: 70px;
  height: 70px;
  background: #ffd740;
  top: 35%;
  right: 40%;
  animation-delay: 30s;
}
.block59 {
  width: 60px;
  height: 60px;
  background: #00e5ff;
  bottom: 25%;
  left: 70%;
  animation-delay: 30.5s;
}
.block60 {
  width: 90px;
  height: 90px;
  background: #ff1744;
  top: 50%;
  right: 80%;
  animation-delay: 31s;
}
.block61 {
  width: 80px;
  height: 80px;
  background: #42b883;
  bottom: 40%;
  left: 60%;
  animation-delay: 31.5s;
}
.block62 {
  width: 75px;
  height: 75px;
  background: #ff9100;
  top: 20%;
  left: 30%;
  animation-delay: 32s;
}
.block63 {
  width: 65px;
  height: 65px;
  background: #536dfe;
  bottom: 60%;
  right: 20%;
  animation-delay: 32.5s;
}
.block64 {
  width: 60px;
  height: 60px;
  background: #ffb6b6;
  top: 12%;
  left: 12%;
  animation-delay: 33s;
}
.block65 {
  width: 80px;
  height: 80px;
  background: #b6ffd6;
  bottom: 22%;
  right: 22%;
  animation-delay: 33.5s;
}
.block66 {
  width: 70px;
  height: 70px;
  background: #b6b6ff;
  top: 32%;
  left: 72%;
  animation-delay: 34s;
}
.block67 {
  width: 90px;
  height: 90px;
  background: #ffd6b6;
  bottom: 42%;
  right: 62%;
  animation-delay: 34.5s;
}
.block68 {
  width: 50px;
  height: 50px;
  background: #d6b6ff;
  top: 52%;
  left: 22%;
  animation-delay: 35s;
}
.block69 {
  width: 100px;
  height: 100px;
  background: #b6ffd6;
  bottom: 62%;
  right: 42%;
  animation-delay: 35.5s;
}
.block70 {
  width: 60px;
  height: 60px;
  background: #b6b6ff;
  top: 72%;
  left: 52%;
  animation-delay: 36s;
}
.block71 {
  width: 80px;
  height: 80px;
  background: #ffd6b6;
  bottom: 82%;
  right: 12%;
  animation-delay: 36.5s;
}
.block72 {
  width: 70px;
  height: 70px;
  background: #ffb6b6;
  top: 22%;
  left: 62%;
  animation-delay: 37s;
}
.block73 {
  width: 90px;
  height: 90px;
  background: #b6ffd6;
  bottom: 32%;
  right: 72%;
  animation-delay: 37.5s;
}
.block74 {
  width: 50px;
  height: 50px;
  background: #b6b6ff;
  top: 42%;
  left: 32%;
  animation-delay: 38s;
}
.block75 {
  width: 100px;
  height: 100px;
  background: #ffd6b6;
  bottom: 52%;
  right: 22%;
  animation-delay: 38.5s;
}
.block76 {
  width: 60px;
  height: 60px;
  background: #d6b6ff;
  top: 62%;
  left: 42%;
  animation-delay: 39s;
}
.block77 {
  width: 80px;
  height: 80px;
  background: #ffb6b6;
  bottom: 72%;
  right: 52%;
  animation-delay: 39.5s;
}
.block78 {
  width: 70px;
  height: 70px;
  background: #b6ffd6;
  top: 82%;
  left: 12%;
  animation-delay: 40s;
}
.block79 {
  width: 90px;
  height: 90px;
  background: #b6b6ff;
  bottom: 12%;
  right: 82%;
  animation-delay: 40.5s;
}
.block80 {
  width: 50px;
  height: 50px;
  background: #ffd6b6;
  top: 12%;
  left: 82%;
  animation-delay: 41s;
}

@keyframes float {
  0% {
    transform: translateY(0) scale(1);
  }
  100% {
    transform: translateY(-40px) scale(1.08);
  }
}
</style>

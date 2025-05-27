<script setup>
// Import the github SVG
import githubIcon from '../assets/gh.svg'
</script>

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
  </div>
  <div class="portfolio">
    <h1>👋 Hi, I'm Vencordthemer!</h1>
    <!-- Main GitHub profile link -->
    <a
      href="https://github.com/vencordthemer"
      target="_blank"
      rel="noopener"
      class="github-link"
    >
      <img :src="githubIcon" alt="GitHub" class="github-icon" />
    </a>
    <section class="about">
      <h2>🧠 About Me</h2>
      <p>
        I'm a passionate <strong>full-stack developer</strong> and toolmaker
        with a focus on performance, clean UIs, and automation.<br />
        I build modern web apps, Discord bots, VS Code extensions, and developer
        tools — often from scratch.<br />
        I love turning ideas into polished, usable products.
      </p>
    </section>

    <section class="projects">
      <!-- Each project card starts with a GitHub icon link to its repo -->
      <h2>🔧 Projects</h2>
      <ul>
        <li>
          <a
            href="https://github.com/vencordthemer/linky"
            target="_blank"
            rel="noopener"
            class="project-gh"
          >
            <img :src="githubIcon" alt="GitHub" class="github-icon-project" />
          </a>
          <strong>Linky</strong>: A Linktree-style profile page builder using
          Firebase for auth and data storage, and Vite + React for the frontend.
          Fast, responsive, and hosted on Cloudflare Pages.
        </li>

        <li>
          <a
            href="https://github.com/vencordthemer/chatzy"
            target="_blank"
            rel="noopener"
            class="project-gh"
          >
            <img :src="githubIcon" alt="GitHub" class="github-icon-project" />
          </a>
          <strong>Chatzy</strong>: A real-time chat app like Discord, built with
          Firebase backend and custom UI. Fully functional with authentication,
          message threads, and a modern design.
        </li>

        <li>
          <a
            href="https://github.com/vencordthemer/simplecli"
            target="_blank"
            rel="noopener"
            class="project-gh"
          >
            <img :src="githubIcon" alt="GitHub" class="github-icon-project" />
          </a>
          <strong>Climenus</strong>: A Python CLI menu library (<code
            >from cli import Menu</code
          >) designed for rapid prototyping and tool building. Ideal for
          interactive terminal tools with zero boilerplate.
        </li>
        <li>
          <a
            href="https://github.com/vencordthemer/slaypoints"
            target="_blank"
            rel="noopener"
            class="project-gh"
          >
            <img :src="githubIcon" alt="GitHub" class="github-icon-project" />
          </a>
          <strong>Slaypoints</strong>: A simple web application for tracking
          loyalty points (SlayPoints), built with React (using Vite) and
          Firebase.
        </li>
        <li>
          <a
            href="https://github.com/vencordthemer/burple"
            target="_blank"
            rel="noopener"
            class="project-gh"
          >
            <img :src="githubIcon" alt="GitHub" class="github-icon-project" />
          </a>
          <strong>Burple Theme (VS Code)</strong>: A custom VS Code theme with
          vibrant black and purple aesthetics. Comes in Burple Dark and Burple
          Light modes, packaged as a .vsix.
        </li>
      </ul>
    </section>

    <section class="stack">
      <h2>📁 My Stack</h2>
      <ul>
        <li><strong>Frontend:</strong> React, Vite, Tailwind</li>
        <li><strong>Backend:</strong> Firebase, Supabase, Express, Node.js</li>
        <li><strong>Languages:</strong> JavaScript, Python, HTML/CSS</li>
      </ul>
    </section>
  </div>

  <div class="footer">
    <a href="https://github.com/vencordthemer/site"> View source code </a>
  </div>
</template>

<style scoped>
/* --- Floating blocks for playful animated background --- */
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
  animation: float 3.5s ease-in-out infinite alternate;
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
@keyframes float {
  0% {
    transform: translateY(0) scale(1);
  }
  100% {
    transform: translateY(-40px) scale(1.08);
  }
}
/* --- End Floating blocks --- */

/* Force white background on all platforms */
:global(body) {
  background: #fff !important;
}

/* Main GitHub profile link styling */
.github-link {
  display: inline-block;
  margin-bottom: 1.5rem;
  margin-left: 0.5rem;
  vertical-align: middle;
}

/* Project GitHub icon styling */
.project-gh {
  display: inline-block;
  margin-right: 0.5em;
  vertical-align: middle;
}
.github-icon-project {
  width: 22px;
  height: 22px;
  vertical-align: middle;
  filter: grayscale(0.2) brightness(0.9);
  transition: transform 0.2s;
}
/* Animate project GitHub icon on hover */
.project-gh:hover .github-icon-project {
  transform: scale(1.15) rotate(-8deg);
  filter: none;
}

/* Main GitHub icon styling */
.github-icon {
  width: 42px;
  height: 42px;
  transition: transform 0.2s;
  vertical-align: middle;
  filter: grayscale(0.2) brightness(0.9);
}
.github-link:hover .github-icon {
  transform: scale(1.15) rotate(-8deg);
  filter: none;
}

/* Portfolio card styling */
.portfolio {
  position: relative;
  width: 90%;
  max-width: 700px;
  margin: 2rem auto;
  padding: 2rem 2.5rem;
  background: #fffbe7 !important;
  border-radius: 18px;
  box-shadow: 0 6px 24px #0001;
  font-family: 'Comic Neue', 'Comic Sans MS', 'Comic Sans', sans-serif;
  color: #22223b;
  z-index: 1;
}

.footer {
  font-family: 'Comic Neue', 'Comic Sans MS', 'Comic Sans', sans-serif;
  transition: transform 0.25s cubic-bezier(0.4, 1.4, 0.6, 1);
}

.footer:hover {
  transform: scale(1.08);
}

@media (max-width: 600px) {
  .portfolio {
    padding: 1rem 0.5rem;
    font-size: 0.98em;
  }
  h1 {
    font-size: 2rem;
  }
  h2 {
    font-size: 1.2rem;
  }
}
h1 {
  font-size: 2.5rem;
  margin-bottom: 0.5em;
  color: #6c63ff;
}
h2 {
  margin-top: 1.5em;
  color: #ff8c00;
}
.about p {
  font-size: 1.15em;
  margin-bottom: 1.5em;
}
.projects ul,
.stack ul {
  list-style: none;
  padding: 0;
}
.projects li,
.stack li {
  margin-bottom: 1em;
  background: #f9f7fd;
  border-radius: 8px;
  padding: 0.7em 1em;
  box-shadow: 0 2px 8px #0001;
}
code {
  background: #eee;
  border-radius: 4px;
  padding: 2px 6px;
  font-size: 0.95em;
  color: #6c63ff;
}
</style>

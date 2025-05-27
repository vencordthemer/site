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
        I'm a passionate <strong>full-stack developer</strong> and toolmaker with a focus on performance, clean UIs, and automation.<br>
        I build modern web apps, Discord bots, VS Code extensions, and developer tools — often from scratch.<br>
        I love turning ideas into polished, usable products.
      </p>
    </section>

    <section class="projects">
         <!-- Each project card starts with a GitHub icon link to its repo -->
      <h2>🔧 Projects</h2>
      <ul>
  <li>
    <a href="https://github.com/vencordthemer/linky" target="_blank" rel="noopener" class="project-gh">
      <img :src="githubIcon" alt="GitHub" class="github-icon-project" />
    </a>
    <strong>Linky</strong>:  A Linktree-style profile page builder using Firebase for auth and data storage, and Vite + React for the frontend. Fast, responsive, and hosted on Cloudflare Pages.
  </li>
  
        <li>
              <a href="https://github.com/vencordthemer/chatzy" target="_blank" rel="noopener" class="project-gh">
      <img :src="githubIcon" alt="GitHub" class="github-icon-project" />
    </a>
          <strong>Chatzy</strong>: A real-time chat app like Discord, built with Firebase backend and custom UI. Fully functional with authentication, message threads, and a modern design.
        </li>

        <li>
              <a href="https://github.com/vencordthemer/simplecli" target="_blank" rel="noopener" class="project-gh">
      <img :src="githubIcon" alt="GitHub" class="github-icon-project" />
    </a>
          <strong>Climenus</strong>: A Python CLI menu library (<code>from cli import Menu</code>) designed for rapid prototyping and tool building. Ideal for interactive terminal tools with zero boilerplate.
        </li>
        <li>
              <a href="https://github.com/vencordthemer/burple" target="_blank" rel="noopener" class="project-gh">
      <img :src="githubIcon" alt="GitHub" class="github-icon-project" />
    </a>
          <strong>Burple Theme (VS Code)</strong>: A custom VS Code theme with vibrant black and purple aesthetics. Comes in Burple Dark and Burple Light modes, packaged as a .vsix.
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
  animation: float 12s ease-in-out infinite alternate;
}
/* Individual floating block positions, colors, and delays */
.block1 { width: 180px; height: 180px; background: #6c63ff; top: 8%; left: 10%; animation-delay: 0s; }
.block2 { width: 120px; height: 120px; background: #ff8c00; bottom: 12%; right: 14%; animation-delay: 2s; }
.block3 { width: 90px; height: 90px; background: #42b883; top: 60%; left: 70%; animation-delay: 4s; }
.block4 { width: 100px; height: 100px; background: #00bcd4; top: 20%; right: 20%; animation-delay: 1s; }
.block5 { width: 70px; height: 70px; background: #ff5ca7; bottom: 30%; left: 25%; animation-delay: 3s; }
.block6 { width: 110px; height: 110px; background: #ffd600; top: 40%; left: 5%; animation-delay: 2.5s; }
.block7 { width: 80px; height: 80px; background: #8e44ad; bottom: 18%; right: 30%; animation-delay: 5s; }
.block8 { width: 60px; height: 60px; background: #00e676; top: 75%; left: 15%; animation-delay: 6s; }
.block9 { width: 130px; height: 130px; background: #e17055; top: 10%; right: 40%; animation-delay: 3.5s; }
.block10 { width: 90px; height: 90px; background: #00bfae; bottom: 8%; left: 60%; animation-delay: 7s; }
.block11 { width: 75px; height: 75px; background: #f50057; top: 50%; right: 10%; animation-delay: 4.5s; }
.block12 { width: 60px; height: 60px; background: #ffb300; bottom: 40%; left: 80%; animation-delay: 8s; }
.block13 { width: 100px; height: 100px; background: #3949ab; top: 30%; left: 50%; animation-delay: 9s; }

@keyframes float {
  0% { transform: translateY(0) scale(1);}
  100% { transform: translateY(-40px) scale(1.08);}
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
.projects ul, .stack ul {
  list-style: none;
  padding: 0;
}
.projects li, .stack li {
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

<script setup>
// Import the github SVG
import githubIcon from "../assets/gh.svg";
</script>

<template>
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
  font-family: "Comic Neue", "Comic Sans MS", "Comic Sans", sans-serif;
  color: #22223b;
  z-index: 1;
}

.footer {
  font-family: "Comic Neue", "Comic Sans MS", "Comic Sans", sans-serif;
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


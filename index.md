---
layout: post
title: Portfolio Home
hide: true
show_reading_time: false
---

<style>
.portfolio-hero {
  padding: 2rem;
  margin: 1rem 0 2rem;
  border: 1px solid #4f8cff;
  border-radius: 16px;
  background: linear-gradient(135deg, rgba(79,140,255,.18), rgba(123,97,255,.10));
}
.portfolio-links {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(190px, 1fr));
  gap: 12px;
  margin: 1rem 0 2rem;
}
.portfolio-card {
  display: block;
  padding: 1rem;
  border: 1px solid rgba(127,127,127,.45);
  border-radius: 12px;
  text-decoration: none;
  transition: transform .2s ease, border-color .2s ease;
}
.portfolio-card:hover, .portfolio-card:focus {
  transform: translateY(-3px);
  border-color: #4f8cff;
}
.portfolio-card strong {
  display: block;
  margin-bottom: .35rem;
}
</style>

<section class="portfolio-hero">
  <p>AP Computer Science Principles Portfolio</p>
  <h1>Arya Taghavi Zargar</h1>
  <p>I am a Del Norte High School student who likes video games interested in electrical engineering, aerospace engineering, programming, tennis, gaming, and photography. This portfolio documents what I build, the problems I encounter, and how my skills improve through each sprint.</p>
</section>

## Onboarding Challenge: Ground 0

My Ground 0 work connects three parts of the onboarding sprint into one workflow:

1. [Tools and Equipment Setup](https://pages.opencodingsociety.com/tools/csp/)
2. [GitHub Pages About Page](https://pages.opencodingsociety.com/github/pages/about/csp/) and [GitHub Pages Home Page](https://pages.opencodingsociety.com/github/pages/csp/)
3. [Onboarding Challenge - Ground 0](https://pages.opencodingsociety.com/sprint1/challenge/csp/)

The setup work gives me a working development environment, GitHub Pages publishes my work, and Ground 0 helps me reflect on the evidence, rankings, teamwork, and skills I still need to improve.

<div class="portfolio-links">
  <a class="portfolio-card" href="{{ '/about/' | relative_url }}">
    <strong>About Me</strong>
    Learn about my interests, background, goals, and the experiences that influence my work.
  </a>
  <a class="portfolio-card" href="https://github.com/aRYA622-y/portfolio">
    <strong>Portfolio Repository</strong>
    View the source files, commit history, issues, and GitHub Pages workflow for this site.
  </a>
  <a class="portfolio-card" href="https://github.com/ruhaanb622/portfolio">
    <strong>Ruhaan's Portfolio</strong>
    Visit one teammate's repository and compare our onboarding progress and evidence.
  </a>
</div>

## Development Environment

<div class="portfolio-links">
  <a class="portfolio-card" href="https://opencodingsociety.com">
    <strong>Open Coding Society</strong>
    Course resources, challenges, and technical references.
  </a>
  <a class="portfolio-card" href="https://github.com/aRYA622-y/portfolio">
    <strong>GitHub</strong>
    Version control, issues, commits, Actions, and Pages deployment.
  </a>
  <a class="portfolio-card" href="https://vscode.dev/">
    <strong>VS Code</strong>
    My main environment for editing, testing, and organizing code.
  </a>
</div>

## GitHub Pages Learning

These resources explain the parts that turn repository files into a published portfolio. I included them so I can move from editing a template to understanding how the site is organized and deployed.

<div class="portfolio-links">
  <a class="portfolio-card" href="https://pages.opencodingsociety.com/github/pages/csp/"><strong>Pages Home</strong>Build and personalize the main portfolio page.</a>
  <a class="portfolio-card" href="https://pages.opencodingsociety.com/github/pages/about/csp/"><strong>About Page</strong>Use Markdown, HTML, CSS, and JavaScript to introduce myself.</a>
  <a class="portfolio-card" href="https://pages.opencodingsociety.com/tools/csp/"><strong>Tools</strong>Set up the editor, terminal, Git, and course workflow.</a>
  <a class="portfolio-card" href="https://pages.opencodingsociety.com/sprint1/challenge/csp/"><strong>Ground 0</strong>Connect evidence, reflection, teamwork, and next steps.</a>
</div>

## Lessons and Projects

<div class="portfolio-links">
  <a class="portfolio-card" href="{{ '/code/javascript' | relative_url }}"><strong>JavaScript Basics</strong>Practice the core syntax used for interactive pages.</a>
  <a class="portfolio-card" href="{{ '/game/essentials/variables' | relative_url }}"><strong>Variables</strong>Explore how programs store and update information.</a>
  <a class="portfolio-card" href="{{ '/gamerunner' | relative_url }}"><strong>Game Runner</strong>Test programs in a browser-based environment.</a>
  <a class="portfolio-card" href="{{ '/network/stack' | relative_url }}"><strong>Networking</strong>Study how information moves between systems.</a>
</div>

## Class Progress

<div class="portfolio-links">
  <a class="portfolio-card" href="{{ '/snake' | relative_url }}"><strong>Snake</strong>A browser game demonstrating logic and interaction.</a>
  <a class="portfolio-card" href="{{ '/gamify/parallax' | relative_url }}"><strong>Fish</strong>A visual project using movement and layered design.</a>
  <a class="portfolio-card" href="{{ '/gamify' | relative_url }}"><strong>Gamify</strong>Course concepts presented through interactive challenges.</a>
  <a class="portfolio-card" href="{{ '/cs-pathway' | relative_url }}"><strong>CS Pathway</strong>My progress through computer science topics.</a>
</div>

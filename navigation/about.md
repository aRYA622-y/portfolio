---
layout: post
title: About Arya
permalink: /about/
comments: true
---

<style>
.about-hero {
  padding: 2rem;
  border-radius: 16px;
  background: linear-gradient(135deg, rgba(79,140,255,.18), rgba(123,97,255,.10));
  border: 1px solid #4f8cff;
  margin-bottom: 1.5rem;
}
.about-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(210px, 1fr));
  gap: 14px;
  margin: 1rem 0 2rem;
}
.about-card {
  padding: 1rem;
  border: 1px solid rgba(127,127,127,.45);
  border-radius: 12px;
  transition: transform .2s ease, border-color .2s ease;
}
.about-card:hover, .about-card:focus-within {
  transform: translateY(-3px);
  border-color: #4f8cff;
}
.about-card h3 { margin-top: 0; }
.place-card { text-align: center; }
.place-card img {
  width: 100%;
  height: 110px;
  object-fit: contain;
}
</style>

<section class="about-hero">
  <p>Student, developer, athlete, and creator</p>
  <h1>Hi, I am Arya.</h1>
  <p>I am a junior at Del Norte High School. I enjoy solving problems with math, science, engineering, and code, especially when I can connect an idea to something I can build and test.</p>
</section>

## My Interests

<div class="about-grid">
  <article class="about-card"><h3>Engineering</h3><p>I am interested in electrical and aerospace engineering. I like understanding how systems work and using math and physics to design practical solutions.</p></article>
  <article class="about-card"><h3>Computer Science</h3><p>I am developing my skills with GitHub, VS Code, Markdown, HTML, CSS, JavaScript, and Python. My goal is to become more independent at testing and debugging.</p></article>
  <article class="about-card"><h3>Tennis</h3><p>Tennis has taught me persistence and adaptation. I played JV and finished a season with only one loss across 22 matches, and I am working toward varsity.</p></article>
  <article class="about-card"><h3>Photography</h3><p>Through AP 2D Art and Design, I explored how people can overlook the nature and beauty near their own homes while searching for it somewhere far away.</p></article>
  <article class="about-card"><h3>Gaming</h3><p>Gaming is one of the ways I relax and spend time with friends. It also makes me curious about the systems, rules, and code behind interactive experiences.</p></article>
  <article class="about-card"><h3>Academics</h3><p>My current STEM coursework includes AP Biology, AP Physics C: Mechanics, AP Calculus BC, and AP Computer Science Principles.</p></article>
</div>

## Background

My family is from Iran, and I have grown up in San Diego. Both are important parts of my identity. The interactive cards below are generated with JavaScript from a small data array, connecting personal information to the coding skills used in this portfolio.

<div class="about-grid" id="place-grid" aria-live="polite"></div>

<script>
const places = [
  {
    name: "California",
    detail: "The place I call home and where I attend school.",
    image: "https://upload.wikimedia.org/wikipedia/commons/0/01/Flag_of_California.svg"
  },
  {
    name: "Iran",
    detail: "My family's culture and heritage.",
    image: "https://upload.wikimedia.org/wikipedia/commons/c/ca/Flag_of_Iran.svg"
  }
];

const placeGrid = document.getElementById("place-grid");

places.forEach((place) => {
  const card = document.createElement("article");
  card.className = "about-card place-card";

  const image = document.createElement("img");
  image.src = place.image;
  image.alt = `${place.name} flag`;
  image.loading = "lazy";

  const title = document.createElement("h3");
  title.textContent = place.name;

  const description = document.createElement("p");
  description.textContent = place.detail;

  card.append(image, title, description);
  placeGrid.appendChild(card);
});
</script>

## What I Am Working Toward

I want to improve at turning ideas into tested programs, documenting mistakes instead of hiding them, and contributing consistently to a team workflow. During Ground 0, I am building a foundation with my development tools, GitHub workflow, Pages portfolio, and sprint reflection.

My strongest self-ranked areas are attendance and timeliness, while learning through mistakes and help seeking are also developing strengths. My lower technical rankings show that I am still early in this course, especially with VS Code, portfolio development, layout, JavaScript challenges, and technical communication. These scores are a starting point, not a final result, and I will use future commits and issues to show improvement.

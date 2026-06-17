---
layout: default
title: Sihui Xue
permalink: /
---

<style>
  :root {
    --global-code-bg-color: rgba(14, 165, 233, 0.08);
    --global-theme-color: #0ea5e9;
    --global-hover-color: #0284c7;
    --global-hover-text-color: #ffffff;
    --global-divider-color: rgba(14, 165, 233, 0.18);
    --global-highlight-color: #bae6fd;
    --global-back-to-top-bg-color: rgba(14, 165, 233, 0.4);
    --global-newsletter-bg-color: #f0f9ff;
    --global-newsletter-button-bg-color: #0ea5e9;
  }

  html[data-theme="dark"] {
    --global-code-bg-color: rgba(56, 189, 248, 0.12);
    --global-theme-color: #38bdf8;
    --global-hover-color: #7dd3fc;
    --global-hover-text-color: #082f49;
    --global-divider-color: rgba(125, 211, 252, 0.24);
    --global-highlight-color: #075985;
    --global-back-to-top-bg-color: rgba(56, 189, 248, 0.35);
    --global-newsletter-bg-color: #082f49;
    --global-newsletter-button-bg-color: #38bdf8;
  }

  .post,
  .post .container {
    max-width: none;
  }

  .academic-home {
    display: grid;
    grid-template-columns: minmax(190px, 250px) minmax(0, 1fr);
    gap: clamp(2rem, 5vw, 4.5rem);
    align-items: start;
    max-width: 1120px;
    margin: 0 auto;
    padding: 2.25rem 1rem 4rem;
  }

  .academic-sidebar {
    position: sticky;
    top: 6rem;
  }

  .academic-profile-image {
    width: min(100%, 190px);
    aspect-ratio: 1;
    border-radius: 50%;
    object-fit: cover;
    display: block;
    margin-bottom: 1.35rem;
    border: 1px solid var(--global-divider-color);
    background: var(--global-card-bg-color);
  }

  .academic-sidebar h2 {
    font-size: 1.15rem;
    line-height: 1.25;
    margin: 0 0 0.55rem;
    font-weight: 700;
  }

  .academic-sidebar p {
    margin: 0 0 1.1rem;
    line-height: 1.55;
    color: var(--global-text-color-light);
  }

  .academic-contact-list {
    display: grid;
    gap: 0.55rem;
    margin: 1.25rem 0 0;
    padding: 0;
    list-style: none;
  }

  .academic-contact-list a,
  .academic-contact-list span {
    display: inline-flex;
    align-items: center;
    gap: 0.55rem;
    min-height: 1.5rem;
    color: var(--global-text-color-light);
    text-decoration: none;
  }

  .academic-contact-list a:hover {
    color: var(--global-theme-color);
    text-decoration: none;
  }

  .academic-contact-list i {
    width: 1.1rem;
    text-align: center;
    color: var(--global-text-color);
  }

  .academic-content {
    min-width: 0;
    max-width: 760px;
    font-size: 1.03rem;
    line-height: 1.72;
  }

  .academic-content h1 {
    margin-top: 0;
    margin-bottom: 1rem;
    font-size: clamp(2rem, 4vw, 2.65rem);
    line-height: 1.1;
    font-weight: 800;
    letter-spacing: 0;
  }

  .academic-content h2 {
    margin-top: 2.25rem;
    margin-bottom: 0.85rem;
    font-size: 1.55rem;
    line-height: 1.2;
    font-weight: 700;
  }

  .academic-content p {
    margin-bottom: 1rem;
  }

  .academic-content ul {
    padding-left: 1.2rem;
  }

  .academic-content li {
    margin-bottom: 0.45rem;
  }

  .academic-content a {
    text-decoration-thickness: 0.08em;
    text-underline-offset: 0.18em;
  }

  @media (max-width: 760px) {
    .academic-home {
      grid-template-columns: 1fr;
      gap: 2rem;
      padding-top: 1.25rem;
    }

    .academic-sidebar {
      position: static;
      display: grid;
      grid-template-columns: 96px minmax(0, 1fr);
      column-gap: 1rem;
      align-items: center;
    }

    .academic-profile-image {
      width: 96px;
      margin: 0;
    }

    .academic-sidebar-main {
      min-width: 0;
    }

    .academic-contact-list {
      grid-column: 1 / -1;
      grid-template-columns: repeat(auto-fit, minmax(9rem, 1fr));
      margin-top: 1rem;
    }
  }
</style>

<div class="academic-home">
  <aside class="academic-sidebar" aria-label="Profile">
    <img class="academic-profile-image" src="{{ '/assets/img/prof_pic.jpg' | relative_url }}" alt="Sihui Xue">

    <div class="academic-sidebar-main">
      <h2>Sihui Xue</h2>
      <p>Personal academic website</p>
    </div>

    <ul class="academic-contact-list">
      <li>
        <span><i class="fa-solid fa-location-dot" aria-hidden="true"></i>Tsukuba, Japan</span>
      </li>
      <li>
        <a href="https://github.com/xue-sihui"><i class="fa-brands fa-github" aria-hidden="true"></i>GitHub</a>
      </li>
      <li>
        <a href="{{ '/cv/' | relative_url }}"><i class="fa-regular fa-file-lines" aria-hidden="true"></i>CV</a>
      </li>
    </ul>

  </aside>

  <main class="academic-content">
    <h1>Sihui Xue</h1>

    <p>
      Welcome to my personal academic website. I use this space to share my research, publications, teaching materials,
      and CV.
    </p>

    <h2>Research</h2>

    <p>My research interests and current work will be added here.</p>

    <h2>Selected Links</h2>

    <ul>
      <li><a href="{{ '/publications/' | relative_url }}">Publications</a></li>
      <li><a href="{{ '/teaching/' | relative_url }}">Teaching</a></li>
      <li><a href="{{ '/cv/' | relative_url }}">CV</a></li>
    </ul>

    <h2>Updates</h2>

    <ul>
      <li>This website is now hosted on GitHub Pages.</li>
    </ul>

  </main>
</div>

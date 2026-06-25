---
layout: page
title: Home
permalink: /
---

<div class="portfolio-page">

<section class="hero" id="about">
  <img src="{{ '/me.jpeg' | relative_url }}" alt="Madison Palmer" class="hero-photo">
  <div>
    <div class="hero-eyebrow">Business Information Systems · BYU</div>
    <h1>Hi, I'm Madison.</h1>
    <p>
      I'm a Business Information Systems student at Brigham Young University with a minor in Statistics.
      I like building things that are useful, thoughtful, and clean, whether that means a full data platform,
      a web app people actually want to open, or a personal project that means something to me.
    </p>
    <p>
      Most of my work sits somewhere between data and design. I enjoy taking messy, real world information
      and turning it into something structured, reliable, and easy to understand. I'm especially interested
      in analytics engineering, full stack development, and machine learning, and I'm always looking for
      projects where I can learn quickly, collaborate well, and ship something I'm proud of.
    </p>
    <p>
      Outside of school, you'll usually find me hiking, spending time outdoors, or working on side projects
      that let me combine creativity with technical problem solving.
    </p>
    <div class="hero-links">
      <a class="button-link" href="#projects">View Projects</a>
      <a class="button-link secondary" href="https://github.com/Mjpalm13" target="_blank" rel="noopener">GitHub Profile</a>
    </div>
  </div>
</section>

<hr class="divider">

<section id="projects">
  <h2>Featured Projects</h2>
  <p class="section-lead">
    A few projects that best represent the kind of work I enjoy, from enterprise analytics
    to full stack web development to a personal religion project I cared deeply about.
  </p>

  <div class="project-grid">

    <article class="project-card featured">
      <div class="project-label">Capstone · IS 566</div>
      <h3>Adventure Works Analytics Data Platform</h3>
      <p>
        My final project for IS 566 at BYU. I built an end to end analytics platform that pulls data from
        PostgreSQL, MongoDB, and a web analytics API, loads it into Snowflake, transforms it with dbt,
        orchestrates the pipeline with Prefect, and exposes the project to AI agents through an MCP server.
      </p>
      <p>
        This was my most technical project to date and gave me hands-on experience with the full analytics
        engineering lifecycle: ingestion, warehousing, modeling, testing, orchestration, and data access for AI agents.
      </p>
      <div class="project-links">
        <a href="https://github.com/Mjpalm13/is-566-final-project" target="_blank" rel="noopener">View Repository</a>
      </div>
      <div class="tech-tags">
        <span class="tech-tag">Snowflake</span>
        <span class="tech-tag">dbt</span>
        <span class="tech-tag">Prefect</span>
        <span class="tech-tag">Python</span>
        <span class="tech-tag">Docker</span>
        <span class="tech-tag">MCP</span>
      </div>
    </article>

    <article class="project-card">
      <div class="project-label">Personal · Religion Project</div>
      <h3>Landscapes of Faith</h3>
      <p>
        A scripture study web app I built for my Book of Mormon class. It combines original landscape
        photography with scripture passages, doctrinal insights, General Conference connections, and
        personal reflection prompts. It works like a digital study journal designed to make scripture study
        feel more personal and visual.
      </p>
      <div class="project-links">
        <a href="https://github.com/Mjpalm13/landscapes-of-faith" target="_blank" rel="noopener">View Repository</a>
        <a href="https://mjpalm13.github.io/landscapes-of-faith/" target="_blank" rel="noopener">Live Site</a>
      </div>
      <div class="tech-tags">
        <span class="tech-tag">React</span>
        <span class="tech-tag">Vite</span>
        <span class="tech-tag">JavaScript</span>
        <span class="tech-tag">CSS</span>
      </div>
    </article>

    <article class="project-card">
      <div class="project-label">Junior Core Capstone</div>
      <h3>INTEX Entertainment Agency Web App</h3>
      <p>
        A full stack application built with React and ASP.NET Core and deployed on Azure. This was the
        capstone for my BYU Information Systems Junior Core experience, covering the full product cycle
        from database design to UI deployment.
      </p>
      <div class="project-links">
        <a href="https://github.com/Mjpalm13/Intex1_15" target="_blank" rel="noopener">View Repository</a>
      </div>
      <div class="tech-tags">
        <span class="tech-tag">React</span>
        <span class="tech-tag">ASP.NET Core</span>
        <span class="tech-tag">Entity Framework</span>
        <span class="tech-tag">Azure</span>
        <span class="tech-tag">SQL Server</span>
      </div>
    </article>

  </div>
</section>

<hr class="divider">

<section id="skills">
  <h2>Technologies I Work With</h2>
  <div class="skills-grid">
    <div class="skill-card">
      <strong>Languages</strong>
      <span>JavaScript, TypeScript, C#, Python, SQL, HTML, CSS</span>
    </div>
    <div class="skill-card">
      <strong>Data & Analytics</strong>
      <span>Snowflake, dbt, Prefect, pandas, data modeling</span>
    </div>
    <div class="skill-card">
      <strong>Frameworks</strong>
      <span>React, ASP.NET Core, Entity Framework, Tailwind, Vite</span>
    </div>
    <div class="skill-card">
      <strong>Tools</strong>
      <span>Azure, GitHub, Docker, VS Code, Postman, SSMS</span>
    </div>
  </div>
</section>

<hr class="divider">

<section>
  <h2>A Little More About Me</h2>
  <div class="about-box">
  <p>
    I'm passionate about collaborative development and bringing ideas to life through code. Some of my
    favorite projects have been the ones where I could build something technically strong and personally
    meaningful at the same time, whether that's a production data platform or a scripture study app I made for class.
  </p>
  <p style="margin-bottom: 0;">
    I'm always looking for opportunities to keep growing, especially in data engineering, analytics,
    and full stack development.
  </p>
  </div>
</section>

</div>

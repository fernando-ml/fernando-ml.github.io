---
layout: profile
permalink: /
title: "Fernando Martínez-López | Reinforcement Learning Research"
excerpt: "Computer Science PhD student at Fordham researching reinforcement learning, world models, and multi-agent adaptation. Seeking summer 2027 research internships."
home: true
---

<section class="profile-intro" aria-labelledby="intro-title">
  <div class="profile-bio">
    <h1 id="intro-title">Fernando Martínez-López</h1>
    <p>I'm a PhD student in Computer Science at Fordham University, supervised by <a href="https://juntaochen1.github.io/">Juntao Chen</a>.</p>
    <p>I study <strong>reinforcement learning</strong>, representation learning, and world models. I connect representation learning and control with game theory and optimization. My current focus is decentralized multi-agent learning using world models.</p>
    <p>My first-author work includes <a href="{{ '/publication/scorer/' | relative_url }}">SCORER</a> (ICLR 2026) and <a href="{{ '/publication/coral/' | relative_url }}">CORAL</a> (IJCAI 2026).</p>
    <p class="internship-note"><strong>I'm looking for a research internship in reinforcement learning for summer 2027.</strong></p>
    <ul class="profile-links" aria-label="Contact and professional profiles">
      <li><a href="mailto:{{ site.author.email }}">Email</a></li>
      <li><a href="{{ '/files/Fernando_Martinez_CV.pdf' | relative_url }}">CV</a></li>
      <li><a href="{{ site.author.googlescholar }}">Google Scholar</a></li>
      <li><a href="https://github.com/{{ site.author.github }}">GitHub</a></li>
      <li><a href="https://www.linkedin.com/in/{{ site.author.linkedin }}">LinkedIn</a></li>
    </ul>
  </div>
  <figure class="profile-portrait"><img src="{{ site.author.avatar | prepend: '/images/' | relative_url }}" alt="Fernando Martínez-López" width="230" height="230"></figure>
</section>

<section class="home-section" id="selected-research" aria-labelledby="publications-title">
  <h2 id="publications-title">Selected research</h2>
  {% assign selected = site.publications | where: 'selected', true | sort: 'feature_order' %}
  {% for paper in selected %}{% include publication-entry.html item=paper details=true figures=true %}{% endfor %}
  <p><a href="{{ '/publications/' | relative_url }}">Full publication list</a></p>
</section>

<section class="home-section" aria-labelledby="experience-title">
  <h2 id="experience-title">Experience</h2>
  {% include experience-list.html limit=3 compact=true %}
  <p><a href="{{ '/cv/' | relative_url }}">Full CV and experience</a></p>
</section>

<section class="home-section" aria-labelledby="personal-title">
  <h2 id="personal-title">Outside research</h2>
  <p>I studied jazz guitar at the Santo Domingo Conservatory for three years. I'm still a jazz nerd, and these days I'm also learning chess.</p>
</section>

<p class="contact-line">You can reach me at <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a>.</p>

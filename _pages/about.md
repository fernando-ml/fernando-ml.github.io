---
layout: profile
permalink: /
title: "Fernando Martínez-López | Reinforcement Learning Research"
excerpt: "Computer Science PhD student at Fordham researching reinforcement learning, world models, and multi-agent adaptation. Seeking summer 2027 research internships."
home: true
---

<section class="hero" aria-labelledby="intro-title">
  <div class="hero-copy">
    <p class="eyebrow">PhD researcher · Fordham University · New York</p>
    <p class="hero-availability">Seeking RL research internships · Summer 2027</p>
    <h1 id="intro-title">Learning to act.<br><em>Learning to adapt.</em></h1>
    <p class="hero-intro">I'm Fernando Martínez-López, a Computer Science PhD student at Fordham University supervised by <a href="https://juntaochen1.github.io/">Juntao Chen</a>. I study <strong>reinforcement learning</strong>: how agents learn useful representations, make decisions, and adapt to unfamiliar environments and other agents.</p>
    <p>My current work explores decentralized multi-agent reinforcement learning using world models. My broader research connects representation learning, control, and game theory.</p>
    <p class="research-credentials">First-author research at <a href="{{ '/publication/scorer/' | relative_url }}">ICLR 2026</a> and <a href="{{ '/publication/coral/' | relative_url }}">IJCAI 2026</a>.</p>
    <div class="hero-actions"><a class="button button--primary" href="{{ '/files/Fernando_Martinez_CV.pdf' | relative_url }}">Download CV <span class="button-note">PDF ↗</span></a><a class="button button--secondary" href="#selected-research">Explore my research ↓</a></div>
    <nav class="profile-links" aria-label="Professional profiles"><a href="{{ site.author.googlescholar }}">Google Scholar ↗</a><a href="https://github.com/{{ site.author.github }}">GitHub ↗</a><a href="https://www.linkedin.com/in/{{ site.author.linkedin }}">LinkedIn ↗</a></nav>
  </div>
  <figure class="hero-portrait"><img src="{{ '/images/PersonalImage.JPG' | relative_url }}" alt="Fernando Martínez-López" width="400" height="400"><figcaption>Research & teaching assistant<br>Computer Science, Fordham University</figcaption></figure>
</section>

<aside class="opportunity" aria-label="Internship availability"><span class="opportunity-dot" aria-hidden="true"></span><div><strong>Seeking summer 2027 research internships</strong><span>Reinforcement learning · World models · Multi-agent learning</span></div><a href="mailto:{{ site.author.email }}">Let's talk <span aria-hidden="true">↗</span></a></aside>

<section class="home-section" id="selected-research" aria-labelledby="research-title">
  <div class="section-heading"><div><p class="eyebrow">Selected research</p><h2 id="research-title">Representations that support better decisions.</h2></div><a class="text-link" href="{{ '/publications/' | relative_url }}">All publications ↗</a></div>
  <div class="featured-research">
    {% assign selected = site.publications | where: 'selected', true | sort: 'feature_order' %}
    {% for paper in selected %}{% include publication-card.html item=paper featured=true %}{% endfor %}
  </div>
  <a class="research-next" href="{{ '/ongoingresearch/' | relative_url }}"><span class="eyebrow">In progress</span><span>Decentralized multi-agent reinforcement learning with world models</span><span aria-hidden="true">→</span></a>
</section>

<section class="home-section" aria-labelledby="experience-title">
  <div class="section-heading"><div><p class="eyebrow">Research meets practice</p><h2 id="experience-title">From applied modeling to adaptive agents.</h2></div><a class="text-link" href="{{ '/cv/' | relative_url }}">Full experience ↗</a></div>
  {% include experience-list.html limit=3 compact=true %}
</section>

<section class="home-section skills-section" aria-labelledby="tools-title"><div><p class="eyebrow">Methods & tools</p><h2 id="tools-title">Theory, implementation, evaluation.</h2></div><div><p>Reinforcement learning, representation learning, world models, game theory, and bilevel optimization.</p><ul class="tag-list" aria-label="Core technical tools">{% for tool in site.data.profile.core_tools %}<li>{{ tool }}</li>{% endfor %}</ul><a class="text-link" href="{{ '/portfolio/' | relative_url }}">Explore implementations & projects ↗</a></div></section>

<section class="contact-panel" aria-labelledby="contact-title"><p class="eyebrow">Summer 2027</p><h2 id="contact-title">Let's build agents that learn and adapt.</h2><p>I'm interested in research scientist internships focused on reinforcement learning, world models, and multi-agent systems. If your team works on these problems, I'd love to connect.</p><a href="mailto:{{ site.author.email }}">{{ site.author.email }} <span aria-hidden="true">↗</span></a></section>

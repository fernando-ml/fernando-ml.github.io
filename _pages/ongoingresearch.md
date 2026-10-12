---
layout: profile
permalink: /ongoingresearch/
title: "Research"
excerpt: "Reinforcement learning research on representation learning, world models, and adaptation to unfamiliar environments and opponents."
---

My research focuses on how agents learn representations that support better decisions and adapt when their environment or opponents change. I am a Computer Science PhD student at Fordham University, supervised by [Juntao Chen](https://juntaochen1.github.io/).

I connect reinforcement learning with game theory and optimization. I study the interaction between representation learning and control, the use of world models for transferring knowledge across tasks, and adaptation in multi-agent settings.

## Research directions

<div class="research-text">
  <h3>Representation learning and control</h3>
  <p>Learning useful features and a policy together can create unstable feedback. I study how game-theoretic coordination and different update timescales can improve this interaction.</p>
  <p><a href="{{ '/publication/scorer/' | relative_url }}">SCORER (ICLR 2026)</a> / <a href="{{ '/publication/sprig/' | relative_url }}">SPRIG (AAAI PRL Workshop 2025)</a></p>
  <h3>World models and transfer</h3>
  <p>What information should an agent carry from one task to another? I explore communicative world models that provide transferable context for learning and adaptation.</p>
  <p><a href="{{ '/publication/coral/' | relative_url }}">CORAL (IJCAI 2026)</a></p>
  <h3>Decentralized multi-agent learning</h3>
  <p>I study how predictive world models can guide agents that learn and act independently from local information.</p>
  <p><a href="#current-work">CASTLE (preprint, 2026)</a></p>
</div>

<section class="research-in-progress" id="current-work" aria-labelledby="current-title">
  <h2 id="current-title">CASTLE: Decentralized MARL with world models</h2>
  <p>CASTLE combines a local dynamics model with a model of the task and social consequences of candidate actions. Both are pretrained offline and frozen to guide independent PPO using local information, without inter-agent communication or a centralized critic.</p>
  <p><a href="{{ '/publication/castle/' | relative_url }}">Independent Multi-Agent Reinforcement Learning with Counterfactual Semantic-Social World Models</a> / <a href="https://arxiv.org/abs/2610.07704">Paper</a></p>
  <p class="status-note">Public preprint, October 2026. Submitted for review.</p>
</section>

<section class="recent-research" aria-labelledby="expert-title">
  <h2 id="expert-title">Ask the Expert: LLM-guided reinforcement learning</h2>
  <p>I also study LLM guidance for autonomous cyber defense. Ask the Expert turns occasional LLM recommendations into reward shaping during PPO training; the deployed policy runs without LLM calls.</p>
  <p><a href="{{ '/publication/ask-the-expert/' | relative_url }}">Paper overview</a> / <a href="https://arxiv.org/abs/2610.09337">Paper</a></p>
  <p class="status-note">Accepted at IEEE GLOBECOM 2026. Proceedings forthcoming.</p>
</section>

## Earlier applied research

My earlier work includes few-shot network attack detection, visual attention, interpretable learning for healthcare, and the evaluation of AI-generated text and images. These projects inform my interest in generalization and careful empirical evaluation.

[Browse all publications]({{ '/publications/' | relative_url }})

<p class="contact-line">I'm seeking summer 2027 research internships in reinforcement learning. <a href="mailto:{{ site.author.email }}">Contact me</a>.</p>

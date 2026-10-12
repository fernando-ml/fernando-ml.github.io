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
  <p>My current work explores decentralized multi-agent reinforcement learning using world models.</p>
  <p><a href="#current-work">Current research</a></p>
</div>

<section class="research-in-progress" id="current-work" aria-labelledby="current-title">
  <h2 id="current-title">Decentralized MARL with world models</h2>
  <p>I am working on decentralized multi-agent reinforcement learning using world models.</p>
  <p class="status-note">Details and public artifacts will be added when available.</p>
</section>

<section class="submitted-research" id="sct" aria-labelledby="sct-title">
  <h2 id="sct-title">Self-Confirming Transformer</h2>
  <p>I have submitted this work on offline multi-agent reinforcement learning and online adaptation to previously unseen, nonstationary opponents.</p>
  <p>The Self-Confirming Transformer (SCT) models an opponent's behavior as a belief and conditions its actions on that belief. Its objective is inspired by self-confirming equilibrium: linking what an agent believes about its opponent to the outcomes it observes.</p>
  <p class="status-note">Submitted for review. A public paper link will be added when available.</p>
</section>

## Earlier applied research

My earlier work includes few-shot network attack detection, visual attention, interpretable learning for healthcare, and the evaluation of AI-generated text and images. These projects inform my interest in generalization and careful empirical evaluation.

[Browse all publications]({{ '/publications/' | relative_url }})

<p class="contact-line">I'm seeking summer 2027 research internships in reinforcement learning. <a href="mailto:{{ site.author.email }}">Contact me</a>.</p>

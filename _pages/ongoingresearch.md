---
layout: profile
permalink: /ongoingresearch/
title: "Research"
excerpt: "Reinforcement learning research on representation learning, world models, and adaptation to unfamiliar environments and opponents."
---

I study how learned representations and predictive models support decision-making in reinforcement learning. My work connects representation learning and control with game theory and optimization, and explores how agents reuse prior knowledge across tasks.

I am a Computer Science PhD student at Fordham University, supervised by [Juntao Chen](https://juntaochen1.github.io/). My current focus is decentralized multi-agent reinforcement learning using world models.

## Research directions

<div class="research-text">
  <h3>Representation learning and control</h3>
  <p>Learning useful features and a policy together can create unstable feedback. SCORER and SPRIG study how game-theoretic coordination between representation learning and control can improve this interaction.</p>
  <p><a href="{{ '/publication/scorer/' | relative_url }}">SCORER (ICLR 2026)</a> / <a href="{{ '/publication/sprig/' | relative_url }}">SPRIG (AAAI PRL Workshop 2025)</a></p>
  <h3>World models and transfer</h3>
  <p>CORAL separates world modeling from control through learned communication. A pretrained information agent provides context that can be reused by a new control agent on unseen tasks.</p>
  <p><a href="{{ '/publication/coral/' | relative_url }}">CORAL (IJCAI 2026)</a></p>
  <h3 id="current-work">Decentralized multi-agent learning</h3>
  <p>CASTLE combines local dynamics and counterfactual social predictions to guide independent PPO. Its world models are pretrained offline and frozen during online learning, with each agent using local information and no inter-agent communication or centralized critic.</p>
  <p><a href="{{ '/publication/castle/' | relative_url }}">CASTLE (preprint, 2026; submitted for review)</a></p>
  <h3>LLM guidance for reinforcement learning</h3>
  <p>Ask the Expert turns occasional LLM recommendations into reward shaping during PPO training for autonomous cyber defense. The deployed policy runs without LLM calls.</p>
  <p><a href="{{ '/publication/ask-the-expert/' | relative_url }}">Ask the Expert (IEEE GLOBECOM 2026; accepted, proceedings forthcoming)</a></p>
</div>

## Earlier applied research

My earlier work includes few-shot network attack detection, visual attention, interpretable learning for healthcare, and the evaluation of AI-generated text and images. These projects inform my interest in generalization and careful empirical evaluation.

[Browse all publications]({{ '/publications/' | relative_url }})

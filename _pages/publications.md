---
layout: profile
title: "Publications"
permalink: /publications/
excerpt: "Research publications by Fernando Martínez-López in reinforcement learning, world models, and applied machine learning, with paper and code links."
---

<p class="page-lead">Reinforcement learning is the focus of my current work. Below are selected RL papers, followed by my broader research.</p>
<p><a href="{{ site.author.googlescholar }}">Google Scholar</a> · <a href="{{ site.author.orcid }}">ORCID</a></p>

<h2>Reinforcement learning</h2>
<div class="publication-list">
{% assign selected = site.publications | where: 'selected', true | sort: 'feature_order' %}
{% for paper in selected %}{% include publication-entry.html item=paper %}{% endfor %}
</div>

<h2>Additional publications</h2>
<div class="publication-list">
{% assign publications = site.publications | sort: 'date' | reverse %}
{% for paper in publications %}{% unless paper.selected or paper.status == 'Submitted manuscript' %}{% include publication-entry.html item=paper %}{% endunless %}{% endfor %}
</div>

<h2>Preprints and submitted manuscripts</h2>
<p class="muted">Listed separately from published and accepted papers, with the status shown for each.</p>
<div class="publication-list">{% for paper in publications %}{% if paper.status == 'Submitted manuscript' %}{% include publication-entry.html item=paper %}{% endif %}{% endfor %}</div>

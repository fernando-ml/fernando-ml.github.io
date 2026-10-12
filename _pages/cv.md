---
layout: profile
title: "CV & experience"
permalink: /cv/
excerpt: "Education, research and industry experience, technical skills, and academic service of Fernando Martínez-López. Download the current CV."
---

<p class="page-lead">Computer Science PhD student researching reinforcement learning, with prior experience building and evaluating applied machine learning and quantitative models.</p>
<div class="cv-actions"><a  href="{{ '/files/Fernando_Martinez_CV.pdf' | relative_url }}">Download CV (PDF)</a><a  href="mailto:{{ site.author.email }}">Contact me</a></div>
<p class="muted">Seeking research scientist internships in reinforcement learning for summer 2027.</p>

<h2>Education</h2>
<div class="experience-list">{% for degree in site.data.profile.education %}<article class="experience-item"><p class="experience-date">{{ degree.dates }}</p><div><h3>{{ degree.degree }}</h3><p class="experience-company">{{ degree.institution }}</p><p>{{ degree.detail }}</p></div></article>{% endfor %}</div>

<h2>Research & industry experience</h2>
{% include experience-list.html %}

<h2>Selected publications</h2>
<div class="publication-list">{% assign selected = site.publications | where: 'selected', true | sort: 'feature_order' %}{% for paper in selected %}{% include publication-entry.html item=paper %}{% endfor %}</div>
<p><a href="{{ '/publications/' | relative_url }}">Full publication list</a></p>

<h2>Technical skills</h2>
<dl class="skills-list">{% for group in site.data.profile.skills %}<dt>{{ group.category }}</dt><dd>{{ group.tools }}</dd>{% endfor %}</dl>

<h2>Honors & awards</h2>
<ul>{% for award in site.data.profile.awards %}<li>{{ award }}</li>{% endfor %}</ul>

<h2>Academic service & volunteering</h2>
<ul><li>Conference reviewer: NeurIPS, ICML, AAAI, and CDC (2026); INFOCOM NGResNet workshop (2025).</li><li>Upcoming conference service: ACC (2027).</li><li>Volunteer, TECHO, Santo Domingo, Dominican Republic.</li></ul>

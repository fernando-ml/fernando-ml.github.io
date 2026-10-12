---
layout: profile
title: "Sitemap"
permalink: /sitemap/
excerpt: "Find all research, publication, project, and CV pages on Fernando Martínez-López's website."
---

## Main pages

* [Home]({{ '/' | relative_url }})
* [Research]({{ '/ongoingresearch/' | relative_url }})
* [Publications]({{ '/publications/' | relative_url }})
* [Projects]({{ '/portfolio/' | relative_url }})
* [CV & experience]({{ '/cv/' | relative_url }})

## Publication details

<ul>{% assign publications = site.publications | sort: 'date' | reverse %}{% for paper in publications %}<li><a href="{{ paper.url | relative_url }}">{{ paper.title }}</a></li>{% endfor %}</ul>

## Project details

<ul>{% assign projects = site.portfolio | sort: 'order' %}{% for project in projects %}<li><a href="{{ project.url | relative_url }}">{{ project.title }}</a></li>{% endfor %}</ul>

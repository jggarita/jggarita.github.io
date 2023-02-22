---
layout: archive
title: "Research"
#excerpt: "Published and Ongoing"
header:
  overlay_image: \LRCornerWallPaper{0.99}{https://jggarita.github.io/images/Header4.jpeg}
  #caption: "From Kepler's Harmonices Mundi"
permalink: /publications/
redirect_from:
  - /research/
  - /research.html
  - /portfolio/
  - /portfolio.html
author_profile: true
---
{% include base_path %}

## Selected Work in Progress
-------

**Elasticity of Taxable Income Under Notches**. *Draft soon*.
- With Luis Fernando Corrales and Claudio Mora.

**Job Displacement Effects and Labor Market Sorting During COVID-19**. *Under Review*.
- With Guillermo Pastrana and Pablo Slon
- Prepared for the CEMLA Joint Research Program 2022

**Minimum Wages and Firm Dynamics: Evidence From Costa Rica's Occupation-Based System**
- New draft soon. Current version here.

**Minimum Wages and Capital-Labor Substitution**
- New draft soon. Current version here.

**Minimum Wages, Firm Pay Policies and Employment Flows**.
- New draft soon. Current version here.

**Labor Market Fluidity in Costa Rica**.



## Working Papers
-------

{% for post in site.publications reversed %}
	{% if post.type == 'progress' %}
		{% include archive-single.html %}
	{% endif%}
{% endfor %}

## Publications
-------

{% for post in site.publications reversed %}
	{% if post.type == 'published' %}
		{% include archive-single.html %}
	{% endif%}
{% endfor %}

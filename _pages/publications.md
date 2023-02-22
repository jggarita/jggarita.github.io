---
layout: archive
title: "Research"
excerpt: "Published and Ongoing"
header:
  overlay_image: https://jgnunol.github.io/images/harmonices.png
  caption: "From Kepler's Harmonices Mundi"
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

**Taxing Sugar-Sweetened Beverages: A Nonlinear Pricing Approach**. *Revise and Resubmit*.
- With [Steven Wu](https://ag.purdue.edu/agecon/Pages/profile.aspx?strAlias=sywu) and [Joseph Balagtas](https://ag.purdue.edu/agecon/Pages/Profile.aspx?strAlias=balagtas).

**Workers, Workplaces, Sorting, and Wage Dispersion in Mexico**. *Under Review*.
- With [Jorge Pérez Pérez](https://jorgeperezperez.com/).

**Approximation in complex pricing mechanisms**.
- With [Jeffrey D. Michler](https://jeffmichler.com/), [Peter Slade](https://sites.google.com/site/sladepeterjoel/), and [Steven Wu](https://ag.purdue.edu/agecon/Pages/profile.aspx?strAlias=sywu).

## Publications
-------

{% for post in site.publications reversed %}
	{% if post.type == 'published' %}
		{% include archive-single.html %}
	{% endif%}
{% endfor %}

## Working Papers
-------

{% for post in site.publications reversed %}
	{% if post.type == 'progress' %}
		{% include archive-single.html %}
	{% endif%}
{% endfor %}





## Links
-------

You can find records of my work in the following links:

* [ORCiD](https://orcid.org/0000-0001-9735-6801)
* [Google Scholar](https://scholar.google.ca/citations?user=udjj4tsAAAAJ&hl=en)
* [RePEc/IDEAS](https://ideas.repec.org/e/pnu115.html)

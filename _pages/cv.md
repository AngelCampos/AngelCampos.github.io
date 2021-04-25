---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Life Sciences, Weizmann Institute of Science, 2021 (expected)
* M.S. in Life Sciences, National Autonomous University of México, 2016
* B.S. in Biology, National Autonomous University of México, 2014

Research Experience
======
* PhD research student: Schraga Schwartz Lab
  * Development of MAZTER-Seq, an anti-body independent method to quantify and map m6A across genomes
  * MAZTER-MINE. A pipeline to analize MAZTER-Seq derived data.
  * STORM-seq, a technology for simultaneous RNA modifications sequencing
* MSc student: Enrique Hernandez Lemus Lab
  * Pathway Analysis: State of the art. A review article on gene-set enrichment analysis tools.
* BSc student: Claudia Segal Kischinevzky
  * Characterization of an acatalasemic S. cerevisiae complemented with catalases from euryhaline D. hansenii

Publications
============
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Software
========
  <ul>{% for post in site.software %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Service and leadership
======
* Member of the Happy hour committee in the Molecular Genetics Department. ;)

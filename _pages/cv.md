---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* **DPhil in Clinical Laboratory Sciences**, University of Oxford, UK

## Current Positions

* **CEO and Chief Scientific Officer**, Continental Molecular Biosystems, Nairobi
* **Founder and Scientific Advisor**, Centre for Molecular Biosciences and Genomics (CMB Genomics), Nairobi
* **Senior Lecturer**, Meru University of Science and Technology, Kenya

## Research Focus

* Population genomics and whole genome sequencing in East African populations
* Pharmacogenomics (CYP2D6, CYP2C19, CYP3A5 and CPIC gene panel)
* Immunogenetics (HLA Class I and II, KIR haplotypes)
* Disease cohort development across metabolic, reproductive, renal, and neuropsychiatric indications
* Multiomics integration
* Antimicrobial resistance surveillance and molecular diagnostics

## Publications

<ul>{% for post in site.publications reversed %}
    <li>{{ post.citation }}</li>
{% endfor %}</ul>

## Talks and Presentations

<ul>{% for post in site.talks reversed %}
    <li>{{ post.title }}, {{ post.date | date: "%Y" }}, {{ post.venue }}</li>
{% endfor %}</ul>

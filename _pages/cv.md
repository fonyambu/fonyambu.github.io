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

* **DPhil in Clinical Laboratory Sciences**, University of Oxford, UK (2009-2014)
  * Thesis: Host adhesion phenotypes for *Plasmodium*-infected erythrocytes; platelet-mediated clumping
  * KEMRI-Wellcome Trust Research Programme
* **BSc in Biochemistry** (Upper Second Class Honours), Moi University, Kenya (2004-2008)
* **Diploma in Medical Laboratory Sciences and Technology**, Kenya Institute of Applied Sciences (2015-2018)

## Current Positions

* **CEO and Chief Scientific Officer**, Continental Molecular Biosystems, Nairobi (2021-present)
* **Founder and Scientific Advisor**, Centre for Molecular Biosciences and Genomics (CMB Genomics), Nairobi (2021-present)
* **Director, Commercial Projects**, Yemaachi Biotech (Jul 2025-present)
* **Senior Lecturer**, Meru University of Science and Technology (2021-present)

## Previous Positions

* **Country Director, Kenya**, Yemaachi Biotech (Mar 2022-Jul 2025)
  * Established and coordinated cancer genomics operations in Kenya
  * Built clinical site networks and managed partnerships with hospitals, oncologists, and pathologists
  * Coordinated national cancer genomics projects
* **Project Laboratory Associate and Lab Manager**, University of Nairobi, Centres of Excellence in HIV Medicine (2016-2021)
  * Launched Sanger DNA sequencing service at the University of Nairobi
  * Managed laboratory operations for infectious disease and drug resistance testing (Sanger and Nanopore)
  * Coordinated establishment of SARS-CoV-2 PCR testing across 15 laboratories during COVID-19
* **Early Stage Researcher and PhD Student**, University of Oxford and KEMRI-Wellcome Trust (2009-2014)
  * Malaria host-parasite interactions using bioinformatics and molecular biology

## Research Focus

* Population genomics and whole genome sequencing across East African populations
* Pharmacogenomics (CYP2D6, CYP2C19, CYP3A5 and CPIC gene panel)
* Immunogenetics (HLA Class I and II, KIR haplotypes)
* Disease cohort development
* Antimicrobial resistance surveillance
* Cancer genomics
* Molecular diagnostics and laboratory systems strengthening

## Skills

* **Sequencing**: Library preparation and sequencing on Illumina and Oxford Nanopore platforms
* **Bioinformatics**: R, Bash, sequencing analysis pipelines, variant calling, microbial genomics
* **Laboratory Management**: ISO 15189, quality management systems for molecular diagnostics
* **Licensing**: Licensed Medical Laboratory Technologist (KMLTTB, 2023)

## Professional Affiliations

* American Society of Human Genetics (ASHG), 2024-present
* International Society for Computational Biology (ISCB)
* Kenya Medical Laboratory Technologists and Technicians Board (KMLTTB)
* Royal Society of Tropical Medicine and Hygiene, Grants and Awards Committee (2022-2024)

## Publications

<ul>{% for post in site.publications reversed %}
    <li>{{ post.citation }}</li>
{% endfor %}</ul>

## Talks and Presentations

<ul>{% for post in site.talks reversed %}
    <li>{{ post.title }}, {{ post.date | date: "%Y" }}, {{ post.venue }}</li>
{% endfor %}</ul>

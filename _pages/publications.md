---
layout: page
permalink: /publications/
title: Publications
description: "* Equal contribution"
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<!-- Each section lists the entries of _bibliography/papers.bib that match its query, in file order. -->

<div class="publications">

<h2 id="preprints">Preprints</h2>

{% bibliography --group_by none --query @unpublished %}

<h2 id="conferences">Conferences</h2>

{% bibliography --query @inproceedings[category=Conference] %}

<h2 id="journals">Journals</h2>

{% bibliography --query @article %}

<h2 id="workshops">Workshops</h2>

{% bibliography --query @inproceedings[category=Workshop] %}

</div>

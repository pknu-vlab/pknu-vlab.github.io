---
layout: page
permalink: /publications/
title: Publications
description: (* Corresponding author, † Equal contribution)
nav: true
nav_order: 4
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2>Submitted</h2>

{% bibliography --query @unpublished %}

{% bibliography --query @*[type!=unpublished] %}

</div>

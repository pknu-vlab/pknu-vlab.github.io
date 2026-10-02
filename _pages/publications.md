---
layout: page
permalink: /publications/
title: Publications
description: (* Corresponding author, † Equal contribution)
nav: true
nav_order: 4
---

{% include bib_search.liquid %}

<div class="publications">

<h2>Submitted</h2>

{% bibliography --query @unpublished --group_by none %}

<h2>Published</h2>

{% bibliography --query @article,@inproceedings --group_by year --group_order descending %}

</div>

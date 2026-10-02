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

{% bibliography --query @unpublished %}

{% bibliography --query @article --group_by year --group_order descending %}
{% bibliography --query @inproceedings --group_by year --group_order descending %}
{% bibliography --query @conference --group_by year --group_order descending %}

</div>

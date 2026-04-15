---
layout: page
permalink: /publications/
title: publications
description: selected publications representing recent and foundational work from the HiACE Lab
nav: true
nav_order: 3
---

{% include bib_search.liquid %}

<div class="publications">
{% bibliography --query @*[selected=true] %}
</div>

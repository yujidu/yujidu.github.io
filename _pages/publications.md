---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
hero_image: berkeley.jpg
---
{% assign gs = site.data.publications.scholar %}
<p class="pub-stats"><a href="{{ gs.url }}">Google Scholar</a>: {{ gs.citations }} citations · h-index {{ gs.h_index }} · i10-index {{ gs.i10_index }} <small>(as of {{ gs.updated }})</small><br><small>* Corresponding author</small></p>

## Journal Articles

<small>First/corresponding-author papers in
 *JMPS* ***2***,
 *CMAME* ***2***,
 *IJNME* ***1***,
 *IJNAMG* ***1***,
 *CG* ***1***,
 *CBM* ***1***,
 *JGGE* ***1***</small>

{% include pub-list.html group="journal" %}

## Chinese Journal Articles

{% include pub-list.html group="chinese" %}

## Manuscripts Under Review

{% include pub-list.html group="under_review" %}

## Conference Papers & Abstracts

{% include pub-list.html group="conference" %}

## Thesis

{% include pub-list.html group="thesis" %}

{% comment %}
Invited talks are hidden for now; delete this comment tag pair to show them again.

## Invited Talks

{% include pub-list.html group="talks" %}
{% endcomment %}

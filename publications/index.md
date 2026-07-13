---
title: Publications
nav:
  order: 3
  # tooltip: Published works
---

# {% include icon.html icon="fa-solid fa-microscope" %}Publications

<!-- We publish high-impact peer-reviewed research papers in leading journals across diverse topics from genomics, epigenomic, machine learning, cancer genomics, and science policy. -->

<!-- ## All publications -->

<div class="button-row">
  {% include button.html text="All" link="/publications/?search=" style="bare" %}
  {% include button.html text="International journal" link="/publications/?search=%22tag:%20international-journal%22" style="bare" %}
  {% include button.html text="International conference" link="/publications/?search=%22tag:%20international-conference%22" style="bare" %}
  {% include button.html text="Domestic paper" link="/publications/?search=%22tag:%20domestic-paper%22" style="bare" %}
  {% include button.html text="Patent" link="/publications/?search=%22tag:%20patents%22" style="bare" %}
</div>

{% include search-box.html disabled=false %}

{% include search-info.html %}

{% include section.html %}

{% include list.html data="citations" component="citation" style="rich" %}


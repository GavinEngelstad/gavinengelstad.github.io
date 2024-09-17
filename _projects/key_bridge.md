---
layout: distill
title: Vulnerability of Urban Road Systems
description: A network analysis of the Baltimore Bridge collapse
img: assets/img/key_bridge/betweenness_diff.png
importance: 3
date: 2024-05-03
category: school
authors:
  - name: Gavin Engelstad
    url: "https://gavinengelstad.github.io"
    affiliations:
      name: Macalester College
---

### Description:

This was my project in [Andrew Beveridge's](https://mathbeveridge.github.io) Network Science class (MATH 479) in Spring 2024.

In it, I sought to use a network model to explore the traffic effects of the [Container Ship *Dali* striking the Key Bridge in Baltimore](https://en.wikipedia.org/wiki/Francis_Scott_Key_Bridge_collapse). My approach used the structure of the road network to identify areas that were the most affected by the collapse. I also did another analysis where I incorporated commuter data to identify areas where the people would be the most affected.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/key_bridge/closeness_w_bridge.png" title="Closeness pre-collapse" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/key_bridge/closeness_wo_bridge.png" title="Closeness post-collapse" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/key_bridge/closeness_diff.png" title="Closeness difference" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: <a href="https://en.wikipedia.org/wiki/Closeness_centrality">Closeness centrality</a> of intersections in the road network before the bridge collapse. Middle: Closeness centrality after the bridge collapse. Right: Change in closeness after the bridge collapse occured.
</div>


### Links:

<div class="links">
    <a href="https://gavinengelstad.github.io/assets/pdf/key_bridge/gavin_netsci.pdf" class="btn btn-sm z-depth-0" role="button">paper</a>
    <a href="https://gavinengelstad.github.io/assets/pdf/key_bridge/gavin_netsci_presentation.pdf" class="btn btn-sm z-depth-0" role="button">slides</a>
    <a href="https://github.com/GavinEngelstad/NetSciBaltimoreBridge" class="btn btn-sm z-depth-0" role="button">code</a>
</div>

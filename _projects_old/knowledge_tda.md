---
layout: distill
title: Topological Data Analysis of Knowledge Networks
img: assets/img/knowledge_tda/know_net.png
importance: 2
date: 2024-11-24
draft: true
category: research
authors:
  - name: Gavin Engelstad
    url: "https://gavinengelstad.github.io"
    affiliations:
      name: Macalester College

  - name: Russell Funk
    url: "https://www.russellfunk.org"
    affiliations:
      name: University of Minnesota

  - name: Frances McConnell
    affiliations:
      name: Macalester College

  - name: Lori Ziegelmeier
    url: "https://www.loriziegelmeier.com"
    affiliations:
      name: Macalester College
---

### Description:

Starting summer 2024, I worked under [Lori Ziegelmeier](https://www.loriziegelmeier.com) and [Russell Funk](https://www.russellfunk.org) to use topological data analysis (TDA) to analyze how knowledge develops over time.

We focus our analysis on knowledge networks constructed by connecting scientific concepts that cooccur in published papers. The TDA tools allow us to analyze where there are missing links in the network between closely related concepts. Using persistent homology (PH) and filtrating over time, we examine how gaps in knowledge open, exist, and close over time.

My role in the project was focused on getting representatives of each of the gaps. PH tools make it easy to pinpoint how many holes there are and when they open or close, but examining exactly what nodes and edges surround the gaps and how they fill in can be harder. I use linear programming to get better representatives of the gaps.

This work inspired my honors project in mathematics, where I looked into new, network-specific approaches to optimizing the representatives of cycles and performed an empirical analysis of the role the papers in the gaps play in scientific literature.

At the 2025 JMM, I presented my work in this project in a special session and the undergraduate poster session. I also presented this in a poster sessions at the 11th annual ATMCS conference.

### Links:

<style>
    .links {
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>

<div class="links">
    <a href="https://gavinengelstad.github.io/assets/pdf/knowledge_tda/paper.pdf" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener noreferrer">paper</a>
    <a href="https://gavinengelstad.github.io/assets/pdf/knowledge_tda/slides.pdf" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener noreferrer">slides</a>
</div>


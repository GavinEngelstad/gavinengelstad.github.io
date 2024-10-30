---
layout: distill
title: Shock Risks and Chokepoint Overreliance
description: Empirical Evidence from the Ever Given Incident
img: assets/img/suez_canal/dist_relia.jpg
importance: 1
date: 2024-05-03
category: school
authors:
  - name: Gavin Engelstad
    url: "https://gavinengelstad.github.io"
    affiliations:
      name: Macalester College
---

This was my project in [Felix Freidt's](https://www.felixfriedt.com) International Trade class (Econ 422) in Spring 2024.

For the project, I was interested in the effects of the container ship Ever Given's crash in the Suez Canal in March 2021. Specifically, I was interested in identifying which ports were initially affected by the crash and the feedback effects from the affected routes' role in global value chains.

To identify initial effects, I used a network model of maritime trade to analyze which ports had the most trade go through the canal and, therefore, were the most exposed to the blockage. I also used my network model to dynamically lag estimates to capture effects when ships that would have been passing through the canal would reach the port, not just while the blockage was going on.

To identify feedback effects, I used Leontief-style input-output analysis. By modeling which parts of the value chain go through the canal, I was able to estimate the aggregate feedback effects of the blockage. The estimated effects I found were in line with estimates from other research, validating the approach.


### Links:

<style>
    .links {
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>

<div class="links">
    <a href="https://gavinengelstad.github.io/assets/pdf/suez_canal/paper.pdf" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener noreferrer">paper</a>
    <a href="https://gavinengelstad.github.io/assets/pdf/suez_canal/slides.pdf" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener noreferrer">slides</a>
    <a href="https://github.com/GavinEngelstad/IntlTradeSuezCanal" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener noreferrer">code</a>
</div>

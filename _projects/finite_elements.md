---
layout: distill
title: A Finite Element Approach to Reaction-Diffusion Systems
img: assets/img/finite_elements/rd_solved.png
importance: 2
date: 2024-12-18
category: school
authors:
  - name: Gavin Engelstad
    url: "https://gavinengelstad.github.io"
    affiliations:
      name: Macalester College
---

### Description:

This was my project in [Will Mitchell's](https://sites.google.com/macalester.edu/willmitchell/home) Partial Differential Equations (MATH 494) class in Fall 2024.

I wanted to explore numerical solvers for partial differential equations. In particular, I looked into how the finite element method of solving PDEs can be applied to reaction-diffusion systems, which often feature highly nonlinear parts that are hard to numerically solve. In Python, I wrote my own reaction diffusion solver. I especially focused on computational efficiency. Using spare matrices, vectorized functions, and efficient linear algebra solvers specific to the features of the problem, the code runs fast, even for large systems.

<div class="col">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/finite_elements/square_ts.png" title="Reaction Difussion equation on a square" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/finite_elements/circle_ts.png" title="Reaction Difussion equation on a circle" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/finite_elements/maze_ts.png" title="Reaction Difussion equation on a maze" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/finite_elements/sphere_ts.png" title="Reaction Difussion equation on a sphere" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/finite_elements/torus_ts.png" title="Reaction Difussion equation on a torus" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Solutions to a reaction diffusion equation over time on various domains.
</div>


### Links:

<style>
    .links {
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>

<div class="links">
    <a href="https://gavinengelstad.github.io/assets/pdf/finite_elements/paper.pdf" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener noreferrer">paper</a>
    <a href="https://gavinengelstad.github.io/assets/pdf/finite_elements/presentation.pdf" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener noreferrer">slides</a>
    <a href="https://github.com/GavinEngelstad/Reaction-Diffusion-FEM" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener noreferrer">code</a>
</div>

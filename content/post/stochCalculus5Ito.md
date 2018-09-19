+++
title = "Stochastic calculus, Part 5(Itô's formula)"
date = 2018-09-19T07:14:00-03:00
draft = false
author= "Rodrigo Bazaes"

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["stochastic integral"]
categories = []

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
# Use `caption` to display an image caption.
#   Markdown linking is allowed, e.g. `caption = "[Image credit](http://example.org)"`.
# Set `preview` to `false` to disable the thumbnail in listings.
[header]
image = ""
caption = ""
preview = true

+++
In this fifth part of the stochastic calculus series, the main ingredient is the powerful Itô's formula, that is the fundamental theorem of stochastic calculus. The most known version is when $f\in C^{2}(\mathbb{R})$ and $(B\_{t})\_{t\geq 0}$ is a 1-dimensional Brownian motion,then $$f(B\_{t})=f(B\_{0})+\int\_{0}^{t}f'(B\_{s})dB\_{s}+\frac{1}{2}\int\_{0}^{t}f''(B\_{s})ds.$$
Here we prove a more general version with semimartingale integrator that includes d-dimensional Brownian motion.After that, some applications are presented, included the transciense and recurrence properties for Brownian motion, the Levy's characterization of Brownian motion, and one version of the  Burkholder-Davis-Gundy inequalities.\\
{{% staticref "itoFormula.pdf" "newtab" %}}Itô's formula{{% /staticref %}}

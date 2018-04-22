+++
title = "Directed Polymers In Random Environment,Part 3"
date = 2018-04-22T07:10:13-03:00
draft = false
author= "Rodrigo Bazaes"

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Polymers"]
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
This is the third part of the notes about Directed Polymers in Random Environment.In this section, we talk about the important martingale $W\_{n}:=\frac{Z\_{n}}{e^{n\lambda(\beta)}}$.By the Martingale Convergence Theorem, the limit $W\_{\infty}:=\lim_{n\to \infty}W\_{n}$ exits $\mathbb{P}-$a.s. Moreover, the limit will be zero almost surely,or strictly positive almost surely. This follows by an application of the $0-1$ Kolmogorov's law. The importance of this martingale is the fact that, as in the temperature case, there is a phase transition that distinguish both cases, and we will have two phases: the weak disorder phase, and the strong disorder phase. It's conjectured that those phases are equivalent to the temperature phases.\
After that, we turn our attention to a particular subset of $\beta's$ and $d\geq 3$, the "$L^{2}$ region". In this region we will have the weak disorder phase, i.e., $W\_{\infty}>0$ $\mathbb{P}-$a.s.Also, we have a diffusive behavior of the polymer ,that is, $|S\_{n}|^{2}\approx n$ when $n$ is large enough,and a local limit theorem is satisfied.\
Finally, we discuss the rate of the martingale convergence.

{{% staticref "polymers ch3.pdf" "newtab" %}}Chapter 3{{% /staticref %}}

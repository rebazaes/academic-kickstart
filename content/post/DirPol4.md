+++
title = "Directed Polymers In Random Environment,Part 4"
date = 2018-05-20T07:16:55-03:00
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
This is the fourth part of the notes about Directed Polymers in Random Environment.In this section, we
consider the semimartingale decomposition of the process $X\_{n}:=-log(W\_{n})$.A key component in this chapter is the random variable $I\_{n}:=\sum\_{x\in \mathbb{Z}^{d}}P\_{n-1}^{\beta,\omega}(S\_{n}=x)^{2}$.In fact, we have the following result:\
**Theorem 1:** Let $\beta\not=0$.Then $$\\{W\_{\infty}=0\\}=\\{ \sum\_{n=1}^{\infty}I\_{n}=\infty\\} ~~ a.s$$
This result is used as follows. We define the *probability of the favorite endpoint of the polymer* as $$J\_{n}:=\max\_{x\in \mathbb{Z}^{d}}P\_{n-1}^{\beta,\omega}(S\_{n}=x)$$
Note that $J\_{n}^{2}\leq I\_{n}\leq J\_{n}$.\
We say that the polymer is *localized* if $$\liminf\_{n\to \infty}\frac{1}{n}\sum\_{t=1}^{n}J\_{t}>0$$
and the polymer is *delocalized* if $$\liminf\_{n\to \infty}\frac{1}{n}\sum\_{t=1}^{n}J\_{t}=0$$
We have this localization transition:\
**Theorem 2:** Let $\beta\not=0$.Then:\
The polymer is localized if and only if $p<\lambda$.\
The polymer is delocalized if and only id $p=\lambda$.\
{{% staticref "polymers ch4.pdf" "newtab" %}}Chapter 4{{% /staticref %}}

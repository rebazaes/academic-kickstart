+++
title = "Stochastic calculus, Part 6(Stochastic differential equations)"
date = 2018-09-30T07:13:35-03:00
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
In this sixth part of the Stochastic Calculus series, we study equations of the type $$
	X(t,\omega)=H(t,\omega)+\int\_{[0,t)}F(s,\omega,X(\omega))dY(s,\omega)
	$$
	Where $X$ is an unknown $\\mathbb{R}^{d}$-valued process.$Y$ is an $\\mathbb{R}^{m}$-valued cadlag semimartingale and $H$ is an $\mathbb{R}^{d}$-valued adapted cadlag process, both given.The coefficient $F(t,\omega,\eta)$ is a $d\times m$-matrix valued function of the time $t$, the sample point $\omega$ and the cadlag path $\eta$.\\
  First we consider some examples. Then we will sutdy the so-called *Itô equations*,that is, equations of the type $$X\_{t}=\xi+\int\_{0}^{t}b(s,X\_{x})ds+\int\_{0}^{t}\sigma(s,X\_{s})dB\_{s}$$ and state existence and uniqueness theorems.\\
  The last section is about the more general semimartingale equation, and also existence and uniqueness resuls. This last section is more technical and the proof are quite long.\\
{{% staticref "SDE.pdf" "newtab" %}}SDE{{% /staticref %}}

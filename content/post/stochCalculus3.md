+++
title = "Stochastic calculus, Part 3"
date = 2018-06-24T07:16:35-03:00
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
This third part of the stochastic calculus series is about stochastic Integral with respect to Brownian motion.This will serve as a warm up to the more general integral with respect to semimartingales. Some ideas are going to be repeated in the next chapter.\
In particlar, we define first the stochastic integral with simple predictable integrands. Then we prove the approximation lemma, that says that the space of simple predictable processes is dense in $\mathcal{L}\_{2}(B)$, that is, the space of measurable, adapted processes $X$ such that $$\left(E\int_{[0,T]}X(t,\omega)^{2}\right)^{\frac{1}{2}}<\infty~~\forall~T<\infty
$$
This allow us to extend the integral to this space.\
Finally, we prove that the linearity holds and the isometry.
\\
{{% staticref "stochIntBM" "newtab" %}}Stochastic integral with respect to Brownian motion{{% /staticref %}}

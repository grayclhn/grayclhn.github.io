---
title: Gray Calhoun’s [ex-]academic homepage
layout: front
---

I’m Gray Calhoun. I started working as an Economist at Amazon in
2017, and worked as an Assistant Professor at Iowa State for 8
years before that. My research focused mostly on time series econometrics
and the bootstrap. I'm not entirely sure what to do with this website now
that I'm in the private sector, but I'll try to keep it at least nominally
up to date while I figure that out.

**Email:** «gcalhou at amazon dot com» (work) and «gray at clhn dot
org» (personal email and IM)

**Links:**
[Resume](dl/calhoun-resume.pdf),
[IDEAS](http://ideas.repec.org/f/pca491.html),
[Google Scholar](http://scholar.google.com/citations?hl=en&user=OS8d9ycAAAAJ),
[LinkedIn](https://linkedin.com/in/grayclhn),
[GitHub](https://github.com/grayclhn),
and [Twitter](https://twitter.com/grayclhn).
Let me know if you want the password to my [family
blog](http://clhn.org). (Don’t feel left out if you don't have it, it’s mostly
pictures of my kids.)

<hr />

## Research in progress

[Out-of-sample comparisons of overfit models](http://lib.dr.iastate.edu/econ_las_workingpapers/14/)
(revise and resubmit at *Quantitative Economics*) with
[supplemental appendix](dl/calhoun_oosoverfit_appendix.pdf) and
[source code archive](dl/calhoun_oosoverfit.zip).
Iowa State University Economics Department Working Paper #11002.
<!-- [Private git repository](https://git.ece.iastate.edu/gcalhoun/oos-overfit) -->

[Improved stepdown methods for asymptotic control of generalized error rates](dl/calhoun_stepdown.pdf)
(revise and resubmit at *Journal of Econometrics*) with
[source code archive](dl/calhoun_stepdown.zip).
<!-- [Private git repository](https://git.ece.iastate.edu/gcalhoun/stepdown-paper/) -->

[An asymptotically normal out-of-sample test based on mixed estimation windows](dl/calhoun_mixedwindow.pdf)
(revise and resubmit at *Econometrica*) with
[source code repository](https://github.com/grayclhn/mixedwindow).

[A method for smoothing Impulse Response Functions for discrete-time linear models](dl/calhoun_smoothirf.pdf)
with [source code archive](https://github.com/grayclhn/smooth_irf).
<!-- [Private git repository](https://git.ece.iastate.edu/gcalhoun/smooth_irf) -->

[A simple block bootstrap for asymptotically normal out-of-sample test statistics](dl/calhoun_oosbootstrap.pdf), with
[source code archive](dl/calhoun_oosbootstrap.zip).
<!-- [Private git repository](https://git.ece.iastate.edu/gcalhoun/oosbootstrap) -->

## Refereed publications

Block bootstrap consistency under weak assumptions.
*Econometric Theory*, 36(6):1383–1406.
[Link](dl/calhoun_bootstrap.pdf),
[published version](https://www.cambridge.org/core/journals/econometric-theory/article/abs/block-bootstrap-consistency-under-weak-assumptions/C50E7F8B46BC2F70CAC9FC4026790B13),
[supplemental appendix](dl/calhoun_bootstrap_appendix.pdf),
and
[public repository](https://github.com/grayclhn/block-bootstrap-weak).

Integrated Assessment Models of the Food, Energy, and Water (FEW) Nexus: A
Review and Research Needs (2016)
with Catherine L. Kling, Raymond W. Arritt, and David A. Keiser.
*Annual Review of Resource Economics*, 9:143–163, 2017.
[Link](https://www.annualreviews.org/doi/abs/10.1146/annurev-resource-100516-033533).

Bootstrap Confidence Intervals for Sharp Regression Discontinuity Designs
with Otávio Bartalotti and Yang He.
*Advances in Econometrics*, 38:421–453, October 2016.
[Link](https://github.com/grayclhn/boot-rd/releases/download/v9/bartalotti_calhoun_he_rdboot.pdf),
[published version](https://www.emerald.com/insight/content/doi/10.1108/S0731-905320170000038018/full/html), and
[source code repository](https://github.com/grayclhn/boot-rd).

Hypothesis testing in linear regression when k/n is large. *Journal
of Econometrics*, 165(2), 2011: 163–174.
[Link](http://www.econ.iastate.edu/research/working-papers/p12216),
[published version](http://www.sciencedirect.com/science/article/pii/S0304407611001448),
[R package](dl/ftestLargeK_1.0.tar.gz), and
[additional files](dl/calhoun_ftest_2010.tar.gz)

## Other working papers

[Research Needs and Challenges in the FEW System: Coupling Economic Models with Agronomic, Hydrologic, and Bioenergy Models for Sustainable Food, Energy, and Water Systems](http://www.card.iastate.edu/publications/dbs/pdffiles/16wp563.pdf),
with Catherine L. Kling, Raymond W. Arritt, David A. Keiser, and 25 others,
March 2016. CARD Working Paper #563.

[A graphical analysis of causality in the Reinhart-Rogoff dataset](dl/calhoun_rrgraphics.pdf)
(2015) with
[source code archive](dl/calhoun_rrgraphics.zip).
Iowa State University Economics Department Working Paper [#15014](https://www.econ.iastate.edu/research/%5Bpublication-menu-cat%5D/p19889).
(This is a more formal version of a blog post I had written earlier.)
<!-- [Private git repository](https://git.ece.iastate.edu/gcalhoun/rr_graphics) -->

<hr />

## Past teaching

* [Principles of Macroeconomics (Econ 102)](102)
* [PhD Econometrics 1 — introduction to statistics
  and regression (Econ 671)](671)
* PhD Macroeconometrics (Econ 674) (moved to Blackboard Learn)
* [Topics in statistical computing (Stat 590f)][590f] ([Heike Hofmann][]
  is teaching it; I’m attending.)
* MA Creative Component (Econ 599): Section CG,
  reference number 3154027
* Research for thesis or dissertation (Econ 699): Section CG,
  reference number 3171027

[590f]: https://github.com/heike/stat590f
[Heike Hofmann]: http://hofmann.public.iastate.edu/

## PhD students

* [Anwen Yin](http://anwenyin.weebly.com). 2015 PhD in Economics,
  [Helle Bunzel](https://www.econ.iastate.edu/people/faculty/bunzel-helle)
  and I were co-advisors.
* [Matt Simpson](http://www.themattsimpson.com/). 2015 PhD in
  Economics and Statitstics, [Jarad Niemi](http://www.jarad.me/) and I
  were co-advisors.

<hr />

## Ephemera

<ul>
{% for post in site.categories.blog %}
<li>
{% if post.link %}
<a href="{{ post.link }}">{{ post.title }}</a> (link, {{ post.date | date_to_string }})
{% else %}
<a href="{{ post.url }}">{{ post.title }}</a> (blog, {{ post.date | date_to_string }})
{% endif %}
</li>
{% endfor %}
</ul>

You can subscribe to the [site’s newsfeed]({{ site.main}}/feed.xml)
for updates.

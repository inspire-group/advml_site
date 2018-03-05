---
layout: post
title: Research Overview
---

The ubiquity of machine learning leads to both opportunities and incentives for attackers to develop strategic approaches to fool learning systems and achieve their malicious goals. Our work in adversarial machine learning at Princeton has two main thrusts: 
* developing attacks on deployed systems to understand their vulnerabilities
* utilizing theoretical insights about learning systems to engineer secure defenses

## Attacks
Autonomous cars are one of the most important upcoming applications of machine learning. Since they interact extensively with the physical world, they present a large attack surface. In particular, their computer vision systems may be vulnerable to adversarial examples. However, in order to attack these systems, _physically robust adversarial_ examples have to be created. We have demonstrated a number of successful real-world attacks called DARTS against a traffic sign recognition pipeline. A more detailed description of this project can be found on this [page]({{ site.baseurl }}{% link darts.md %}). Our work received [coverage on The Register](https://www.theregister.co.uk/2018/02/20/do_you_stop_for_kfc_vehicle_ais_might/).

**Useful Links**: [Paper](https://arxiv.org/abs/1802.06430), [Code](https://github.com/inspire-group/advml-traffic-sign)

## Defenses 
We were the first to explore the use of _dimensionality reduction_ techniques such as PCA to defend against evasion attacks on neural networks. A more detailed description of this project can be found on this [page]({{ site.baseurl }}{% link dtdefense.md %}).

**Useful Links**: [Paper](https://arxiv.org/abs/1704.02654), [Code](https://github.com/inspire-group/ml_defense)

## People
The following researchers at [Princeton University](https://www.princeton.edu/) and [Purdue University](http://www.purdue.edu/) contributed to the projects described above:
* [Arjun Nitin Bhagoji](http://www.princeton.edu/~abhagoji/), Princeton University
* [Arsalan Mosenia](http://arsalanmosenia.com/), Princeton University
* Chawin Sitawarin, Princeton University
* [Mung Chiang](https://engineering.purdue.edu/Engr/People/ptProfile?resource_id=171238), Purdue University
* [Daniel Cullina](https://www.princeton.edu/~dcullina/), Princeton University
* [Prateek Mittal](http://www.princeton.edu/~pmittal/), Princeton University


<!-- Here's the embedded video:
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZWwBotKeqDk" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe> -->

<!-- Lanyon is an unassuming [Jekyll](http://jekyllrb.com) theme that places content first by tucking away navigation in a hidden drawer. It's based on [Poole](http://getpoole.com), the Jekyll butler.

### Built on Poole

Poole is the Jekyll Butler, serving as an upstanding and effective foundation for Jekyll themes by [@mdo](https://twitter.com/mdo). Poole, and every theme built on it (like Lanyon here) includes the following:

* Complete Jekyll setup included (layouts, config, [404](/404), [RSS feed](/atom.xml), posts, and [example page](/about))
* Mobile friendly design and development
* Easily scalable text and component sizing with `rem` units in the CSS
* Support for a wide gamut of HTML elements
* Related posts (time-based, because Jekyll) below each post
* Syntax highlighting, courtesy Pygments (the Python-based code snippet highlighter)

### Lanyon features

In addition to the features of Poole, Lanyon adds the following:

* Toggleable sliding sidebar (built with only CSS) via **☰** link in top corner
* Sidebar includes support for textual modules and a dynamically generated navigation with active link support
* Two orientations for content and sidebar, default (left sidebar) and [reverse](https://github.com/poole/lanyon#reverse-layout) (right sidebar), available via `<body>` classes
* [Eight optional color schemes](https://github.com/poole/lanyon#themes), available via `<body>` classes

[Head to the readme](https://github.com/poole/lanyon#readme) to learn more.

### Browser support

Lanyon is by preference a forward-thinking project. In addition to the latest versions of Chrome, Safari (mobile and desktop), and Firefox, it is only compatible with Internet Explorer 9 and above.

### Download

Lanyon is developed on and hosted with GitHub. Head to the <a href="https://github.com/poole/lanyon">GitHub repository</a> for downloads, bug reports, and features requests.

Thanks! -->

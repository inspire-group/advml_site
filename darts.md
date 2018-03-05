---
layout: page
title: "DARTS: Deceiving autonomous cars with toxic signs"
---

**Useful Links**: [Paper](https://arxiv.org/abs/1802.06430), [Code](https://github.com/inspire-group/advml-traffic-sign)

Autonomous cars are one of the most important new applications where machine learning is used. Computer vision systems that rely on machine learning are a crucial component of autonomous cars. However, these systems are not robust against adversaries who can input images with carefully crafted perturbations designed to cause misclassification. In our paper, we demonstrate that these images pose a threat to _traffic sign recognition_ systems which interact with the physical world. 

<figure>
  <img src="{{site.baseurl}}/assets/diagram_benign.jpg" alt="benign setting" align="middle"/>
  <figcaption> Autonomous car operation under benign conditions.</figcaption>
</figure>

<figure>
  <img src="{{site.baseurl}}/assets/diagram_adv.jpg" alt="benign setting" align="middle"/>
  <figcaption> Autonomous car operation under adversarial conditions.</figcaption>
</figure>


We move beyond attacks that are carried out starting from digital images by printing adversarial examples out on posters and driving by these. We show that adversarial examples can be created starting from arbitrary signs and logos, as well as from traffic signs. Videos of our drive-by tests are below. 

**Adversarial Traffic Sign Drive-by Test**
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZWwBotKeqDk" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

**Custom Sign Drive-by Test**
<iframe width="560" height="315" src="https://www.youtube.com/embed/4oqQJMCAvk4?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
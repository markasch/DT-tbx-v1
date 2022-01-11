---
layout: page
title: biodiversity monitoring
description: sperm whale sonar communication
img: /assets/img/sperm_whale_propa.png
importance: 3
category: environmental
---

The objective is to develop a digital twin of a  sperm-whale in the framework of the national AI chair [ADSIL](https://bioacoustics.lis-lab.fr/). This twin will play an important role in monitoring the biodiversity of this endangered species.

- CNRS Journal made a nice [video](https://youtu.be/Kn_-xLzz5pg) of the preliminary phases of the project.
- A recent [talk](/DT-tbx-v1/assets/pdf/Asch_NN_4_IP.pdf) describes a neural network based approach for solving the related direct and inverse problems. 

The first stages of the twin's development are described in detail in Maxence Ferrari's [thesis](https://hal.archives-ouvertes.fr/tel-03078625). 

The twin will provide a complete emission-transmission-reception chain of the sperm whale's sonar system, which is known to be the most powerful in the animal kingdom. The inverse problem that we want to study entails characterization of the whale's biosonar source signal, its generation, its propagation inside the head---the so-callled leaky bent horn model---and then into the surrounding environment, where it is used for communication and for hunting.

We are currently implementing a comparison between:

- a classical adjoint approach, based on variational calculus, as described in {% cite Asch2016 %}
- a physics-constrained neural network approach, as described in this [blog post](/DT-tbx-v1/blog/2022/nn4pde/) and in the [book](https://www.siam.org/publications/books/book-series).


References
----------

{% bibliography --cited %}

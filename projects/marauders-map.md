---
layout: portfolio
title: Marauder's Map
tags: [Study, Research]
category: portfolio
summary: "Marauder's Map is a location based service to unify offline and online identities."
---
{% include base.html %}
## About
During the course of a seminar two friends and I realized a location based service on our own as a proof of concept.

Our goal was to unify offline and many online identities by having users interact via a map on their iPhones.

I developed the server infrastructure by expanding the XMPP server OpenFire with custom implementations of several [XEPs](http://xmpp.org/xmpp-protocols/xmpp-extensions/). I used [Wokkel](http://wokkel.ik.nu/) which uses [Twisted](http://twistedmatrix.com/trac/) to provide a testing ground for XMPP.

## Details
You can find more details in the [paper]({{ base }}/downloads/LocationBasedSocialServices.pdf).

The source if available under the MIT License [here](https://github.com/blacklab/Marauders-Map-Server-Component).

## Screenshots
![Marauder 1]({{ base }}/public/img/marauder_1.PNG "Marauder 1")
![Marauder 2]({{ base }}/public/img/marauder_2.PNG "Marauder 2")
![Marauder 3]({{ base }}/public/img/marauder_3.PNG "Marauder 3")

---
title: Compute-optimized Blockchain Mempool Tools at BitsMedia
date: 2022-03-05
author: Philipp Bartel
image:
  focal_point: 'top'
---

Philipp wrote the backend of several blockchain tools hosted at one of the oldest blockchain media in existence - bits.media. They include commission, prediction, mining, markets and mempool tools for several cryptocurrencies. The databases and algorithms were done from scratch, working with in-house light nodes, at a fraction of the typical resource costs. 

<!--more-->

Bits.media is a information source about classic and contemporary blockchain applications. This is typically a combination of market and mempool data. Mempool data must come from in-house sources to not be dependent upon external websites.

For this, several blockchain nodes were maintained on an internal server. Several daemons were working with each node application individually. Appropriate databases were designed to allow for online information updates. The successful solution yielded a modular and failure-resistant architecture at a very low maintenanace cost.

Mining calculators and market information pages required both statistical calculations, and online trades information. Around a thousand tradehouse spots were connected to the database online. Untrusted coins had to be filtered out. In this project Phil had to direct and manage the in-house front-end talent as well.

This project started with a straightforward consultation about the expectation times of new blocks; and ended with an easily maintained code-base. This project highlighted our team's ability to design working solutions using limited computational resources.
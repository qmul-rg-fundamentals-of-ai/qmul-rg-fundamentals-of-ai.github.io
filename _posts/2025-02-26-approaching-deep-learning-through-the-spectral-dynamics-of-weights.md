---
layout: post
title: Approaching Deep Learning through the Spectral Dynamics of Weights
date: 2025-02-26 10:30:00
description: Presented by Mark Sandler
tags: arxiv-paper
categories: talks
related_publications: true
---

**[Mark Sandler](https://www.seresearch.qmul.ac.uk/cmai/people/msandler/)** will presenting and dicussing the the paper: Approaching Deep Learning through the Spectral Dynamics of Weights {% cite yunis2024approachingdeeplearningspectral %}

**_Abstract_**

We propose an empirical approach centered on the spectral dynamics of weights---the behavior of singular values and vectors during optimization---to unify and clarify several phenomena in deep learning. We identify a consistent bias in optimization
across various experiments, from small-scale ``grokking'' to large-scale tasks like image classification with ConvNets, image generation with UNets, speech recognition with LSTMs, and language modeling with Transformers. We also demonstrate that weight decay
enhances this bias beyond its role as a norm regularizer, even in practical systems. Moreover, we show that these spectral dynamics distinguish memorizing networks from generalizing ones, offering a novel perspective on this longstanding conundrum. Additionally,
we leverage spectral dynamics to explore the emergence of well-performing sparse subnetworks (lottery tickets) and the structure of the loss surface through linear mode connectivity. Our findings suggest that spectral dynamics provide a coherent framework
to better understand the behavior of neural networks across diverse settings.

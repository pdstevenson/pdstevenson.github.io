---
title: 'New preprint'
date: 2023-08-31
permalink: /posts/2013/08/blog-post-2/
tags:
---

This week my student Lance, along with Jim Al-Khalili and me as supervisors, has uploaded a [new preprint](http://arxiv.org/abs/2308.15425) to the arXiv. 
The work is a simulated quantum computing implementation of the imaginary time evolution algorithm to drive a quantum system from an initial trial wave function to its ground state.  It's a direct mapping of the classical algorithm, and we are able to see by comparison that the quantum version works correctly.  We've applied it to the case of nuclear density functional theory, implemented in the wave function representation (i.e. the Kohn-Sham representation).  Ultimately the problem is then represented by the single particle wave functions making up the nucleus.  We chose the simplest case - spherical helium-4 in which there is only a single unique wave function to have to worry about.  As a follow-on, we are working on the next-simplest case, oxygen-16, in which the nuclear density is made of two wave functions, at least in the simplified nuclear model we are considering.

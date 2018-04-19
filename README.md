# Linear Optimal Low Rank Projection (lolPy)


[![arXiv shield](https://img.shields.io/badge/arXiv-1709.01233-red.svg?style=flat)](https://arxiv.org/abs/1709.01233)
[![Build Status](https://travis-ci.org/j1c/lol.svg?branch=master)](https://travis-ci.org/j1c/lol)

# Overview

Supervised learning techniques designed for the situation when the dimensionality exceeds the sample size have a tendency to overfit as the dimensionality of the data increases. To remedy this High dimensionality; low sample size (HDLSS) situation, we attempt to learn a lower-dimensional representation of the data before learning a classifier. That is, we project the data to a situation where the dimensionality is more manageable, and then are able to better apply standard classification or clustering techniques since we will have fewer dimensions to overfit. A number of previous works have focused on how to strategically reduce dimensionality in the unsupervised case, yet in the supervised HDLSS regime, few works have attempted to devise dimensionality reduction techniques that leverage the labels associated with the data. In this package, we provide several methods for feature extraction, some utilizing labels and some not, along with easily extensible utilities to simplify cross-validative efforts to identify the best feature extraction method. Additionally, we include a series of adaptable benchmark simulations to serve as a standard for future investigative efforts into supervised HDLSS. Finally, we produce a comprehensive comparison of the included algorithms across a range of benchmark simulations and real data applications.

For R implmentation, please [here](https://github.com/neurodata/lol).

# System Requirements

## Hardware Requirements
TODO

## Software Requirements
TODO

### OS Requirements
TODO

# Installation Guide

## Stable Release
`lolPy` will be available on PyPi soon. Stay tuned.
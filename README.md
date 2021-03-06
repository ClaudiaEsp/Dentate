# inet [![Build Status](https://travis-ci.org/JoseGuzman/inet.png?branch=master)](https://travis-ci.org/JoseGuzman/inet)

A python module to test connectivity models 
between [interneurons](https://en.wikipedia.org/wiki/Interneuron) and principal neurons. It is based on multiple simultaneous patch-clamp recordings.

Reference:

Guzman SJ, Schloegl A, Frotscher M and Jonas P (2016) [Synaptic mechanisms of pattern completion in the hippocampal CA3 network](https://www.ncbi.nlm.nih.gov/pubmed/27609885). *Science* 353:1117-1123.

Espinoza C, Guzman SJ, Zhang X and Jonas P (2018) [Parvalbumin+ interneurons obey unique connectivity rules and establish a powerful lateral-inhibition microcircuit in dentate gyrus](https://www.nature.com/articles/s41467-018-06899-3). *Nature Communications* 9:4605

Requirements
============

* Python (tested in 2.7, will not work in Python 3.6)
* NumPy (tested in 1.13)
* Scipy (tested in 0.19)

How to install it
=================

`pip install git+https://github.com/ClaudiaEsp/inet.git`

Basic usage
=================
In python:

```python
from inet import DataLoader
mydataset = Dataloader("./data") # load connectivity matrices
```
A further explanation can be found [here](doc/Reading_matrices.rst)

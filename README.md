[![](https://travis-ci.org/fiji/Directionality.svg?branch=master)](https://travis-ci.org/fiji/Directionality)

Directionality
==============

This Fiji plugin is used to infer the preferred orientation of structures 
present in the input image. It computes a histogram indicating the amount 
of structures in a given direction. Images with completely isotropic content 
are expected to give a flat histogram, whereas images in which there is a 
preferred orientation are expected to give a histogram with a peak at 
that orientation.

A toy extra analysis step fits the histogram with a gaussian to measure
the main orientation and its spread.



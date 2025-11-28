# LRCT – Linear-Region-Based Contour Tracking  

This repository contains the minimal code and example data required to reproduce
the method:

**“Linear-Region-Based Contour Tracking for Edge Images.”**

The provided MATLAB script implements the complete contour-tracking pipeline,
including grayscale conversion, scaling, edge extraction, window-based shape
descriptor computation, and iterative contour following. The correct operation of the edge detection process depends on the proper selection of the parameters used in each stage of the pipeline, as well as appropriate values of db and T, in accordance with the tracking distance and the size of the analysis region.

M01_PRINCIPAL.m – Main demonstration script  

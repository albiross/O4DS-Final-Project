# Optimization for Data Science - Unipd 
## Final Project
### Frank-Wolfe Variants for Semi-Relaxed Optimal Transport
The main task of this work is solving an Optimal Transport (OT) problem applied to the
color transfer field. Due to the various issues that can be encountered while solving it, we tackle
the relaxation approach of the OT problem by relaxing one of its constraints. We solve it using
the Frank-Wolfe algorithm and two of its variants: Block-Coordinate Frank-Wolfe, and Block-
Coordinate Away Frank-Wolfe, which is supposed to give even better results. We employ different
values of the relaxation parameter and/or the number of iterations in order to improve the baseline
results and compare the outputs of the different values used. The assessment was done by analyzing
the objective function and by observing the results of the color-transferred images in each case.

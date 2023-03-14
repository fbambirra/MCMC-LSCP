# MCMC-LSCP
Ox code for MCMC for level-set Cox process
Manuscript: Exact Bayesian inference for level-set Cox processes with piecewise constant intensity function
Authors: Flávio B. Gonçalves and Bárbara C. C. Dias


The algorithms are coded in Ox

Please, download Ox Console (including OxEdit) from the link https://www.doornik.com/download.html.
Ox is free for academic use.

The main file mcmc.ox is the one to be run and contains all the required specifications to be set.

The first row of the data file should contain its number of rows and columns (Ox format).
The first column contains the x coordinates and the second one the y coordinates.
For the spatiotemporal code, the third collumn contains the times (starting at 1).

The covariance function is set in file cov_func.ox - default is the poered exponential with exponent 1.95.

Code for the spatial model is in file spatial.rar.
Code for the spatiotemporal model is in file spatiotemporal.rar.

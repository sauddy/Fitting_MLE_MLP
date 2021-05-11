# Fitting_MLE_MLP

In the following example we want to study the stellar mass
distribution of the Orion Nebula Cluster (ONC) [1, 2] which is a stellar cluster
in the Milky Way. The ONC.dat file contains the different stellar masses. To
obtain the mass function, we plot a histogram with f(m) on the y-axis which
is obtained from the frequency of each mass interval. The mass function of any
stellar cluster has a characteristic peak and a power-law tail.


We fit MLP function, which is a three-parameter probability distribution function. The three parameters of the dis-
tribution function are α0, μ0, and σ0. α0 + 1 is the power-law index of dN/dm
for the power-law distribution: characteristic of a Pareto distribution which is
used to represent pure power-law distributions. The parameters μ0 and σ0^2 are
the same as for the lognormal distribution but do not represent the mean and
variance of the distribution unlike for the lognormal distribution. Parameters
μ0 and σ0 describe the shape of the lognormal-like body and α0 represents the
power-law tail. In the limit as σ0 tends to zero, the function behaves as a pure
power-law.

Please check out the attached PDF for details.

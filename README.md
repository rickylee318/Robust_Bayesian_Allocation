# Robust_Bayesian_Allocation

### Motivation

- Typically, asset allocation is a two-step approach: estimate market distribution (<img src="http://chart.googleapis.com/chart?cht=tx&chl=\mu" style="border:none;">
, <img src="http://chart.googleapis.com/chart?cht=tx&chl=\Sigma" style="border:none;">
), and then perform optimization for asset allocation w.

- However, the second step is very sensitive due to input parameters (<img src="http://chart.googleapis.com/chart?cht=tx&chl=\mu" style="border:none;">
, <img src="http://chart.googleapis.com/chart?cht=tx&chl=\Sigma" style="border:none;">
).

- In order to deal with this issue, robust method provides different approach for estimation risk by giving a uncertain range for parameter

- Bayesian approach is quite nature to identify a suitable uncertainty range for the market parameters <img src="http://chart.googleapis.com/chart?cht=tx&chl=\mu" style="border:none;">
, <img src="http://chart.googleapis.com/chart?cht=tx&chl=\Sigma" style="border:none;">
 (location-dispersion ellipsoid of the posterior distribution)


![](bay_robust_alloc.jpg)

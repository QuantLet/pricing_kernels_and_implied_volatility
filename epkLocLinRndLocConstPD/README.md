<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of QuantLet: epkLocLinRndLocConstPD

Published in: pricing_kernels_and_implied_volatility

Description: 'Estimates and plots (yearly) empirical pricing kernels (EPK), risk neutral densities (RND) and physical densities (PD) of DAX

Keywords: pricing kernel, risk neutral density, physical density, kernel regression, volatility, dax, vdax, kernel, regression, risk, risk aversion

Author: Roman Lykhnenko

Submitted: Roman Lykhnenko

Datafile: 'C_2012.csv, timeSeriesDaxVdax.csv, locLinBW.RData'

Input: 

- timeSeriesDaxVdax.csv: Time series of VDAX-NEW index and DAX 30 index

- C_2012.csv: Call prices 2012

- locLinBW.RData: Bandwidths used for estimation of RND based on local linear kernel regression

Output: 

- epkLocLinRndLocConstPD2012.RData: Estimated conditional pricing kernels, risk neutral and physical densities

- epkLocLinRndLocConstPD_PD_2012.png: Plot of estimated physical densities conditional on 20% (red curve), 40% (green curve) and 60% (blue curve) quantiles of volatility index VDAX-NEW

- epkLocLinRndLocConstPD_PD_CI_2012.png: Plot of estimated physical density conditioned by 40% quantile of VDAX-NEW and time to maturity 1 month with 95% confidence intervals

- epkLocLinRndLocConstPD_PK_2012.png: Plot of estimated pricing kernels conditional on 20% (red curve), 40% (green curve) and 60% (blue curve) quantiles of volatility index VDAX-NEW

- epkLocLinRndLocConstPD_PK_CI_2012.png: Plot of estimated pricing kernel conditioned by 40% quantile of VDAX-NEW and time to maturity 1 month with 95% confidence intervals

- epkLocLinRndLocConstPD_RND_2012.png: Plot of estimated risk neutral densities conditional on 20% (red curve), 40% (green curve) and 60% (blue curve) quantiles of volatility index VDAX-NEW

- epkLocLinRndLocConstPD_RND_CI_2012.png: Plot of estimated risk neutral density conditioned by 40% quantile of VDAX-NEW and time to maturity 1 month with 95% confidence intervals

Example: 'The estimated conditional pricing kernels, risk neutral and physical densities for year

```
<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/pricing_kernels_and_implied_volatility/master/epkLocLinRndLocConstPD/epkLocLinRndLocConstPD_PD_2012.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/pricing_kernels_and_implied_volatility/master/epkLocLinRndLocConstPD/epkLocLinRndLocConstPD_PD_CI_2012.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/pricing_kernels_and_implied_volatility/master/epkLocLinRndLocConstPD/epkLocLinRndLocConstPD_PK_2012.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/pricing_kernels_and_implied_volatility/master/epkLocLinRndLocConstPD/epkLocLinRndLocConstPD_PK_CI_2012.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/pricing_kernels_and_implied_volatility/master/epkLocLinRndLocConstPD/epkLocLinRndLocConstPD_RND_2012.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/pricing_kernels_and_implied_volatility/master/epkLocLinRndLocConstPD/epkLocLinRndLocConstPD_RND_CI_2012.png" alt="Image" />
</div>


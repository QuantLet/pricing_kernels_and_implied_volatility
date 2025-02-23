<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of QuantLet: epk3VolaIntervalsVDAX3m

Published in: pricing_kernels_and_implied_volatility

Description: Estimates and plots (yearly) empirical pricing kernels (EPK), risk neutral densities (RND) and physical densities (PD) of DAX 30 index return conditional on time to maturity 3 months and different levels of VDAX-NEW-Subindex 3 (20 equally spaced numbers from 5% to 95% quantile of VDAX-NEW-Subindex 3 in a given year). Local linear kernel regression is used for estimation of the conditional risk neutral density and local constant kernel regression is used for estimation of conditional physical density. EPK is obtained as a ratio of RND and PD. The panels on the right-hand side of figures depict EPK, RND, PD conditional on 20%, 50% and 80% quantiles of VDAX-NEW-Subindex 3 with 95% confidence intervals. Colors from red to blue correspond to increasing values of volatility within each interval. All results are shown on a continuously compounded 3-months period returns scale.

Keywords: pricing kernel, risk neutral density, physical density, kernel regression, volatility, dax, vdax, kernel, regression, risk, risk aversion

See also: epk3VolaIntervalsVDAX, epk3VolaIntervalsVDAX2m, epk3VolaIntervalsVDAX1m, locLinBW, termStructurePK

Author: Roman Lykhnenko

Submitted: Roman Lykhnenko

Datafile: C_2012vdax3m.csv, timeSeriesDaxVdax3m.csv, locLinBWvdax3m.RData

Input: 
- timeSeriesDaxVdax3m.csv : Time series of VDAX-NEW-Subindex 3 and DAX 30 index
- C_2012vdax3m.csv        : Call prices 2012
- locLinBWvdax3m.RData    : Bandwidths used for estimation of RND based on local linear kernel regression

Output: 
- listRndPDpkVDAX3m2012.RData         : Estimated conditional pricing kernels, risk neutral and physical densities
- epk3VolaIntervalsVDAX3m_RND2012.png : Plot of estimated conditional risk neutral densities
- epk3VolaIntervalsVDAX3m_PD2012.png  : Plot of estimated conditional physical densities
- epk3VolaIntervalsVDAX3m_PK2012.png  : Plot of estimated conditional pricing kernels

Example: The estimated conditional pricing kernels, risk neutral and physical densities for year 2012. For more details see Description.

```
<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/pricing_kernels_and_implied_volatility/master/epk3VolaIntervalsVDAX3m/epk3VolaIntervalsVDAX3m_PD2012.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/pricing_kernels_and_implied_volatility/master/epk3VolaIntervalsVDAX3m/epk3VolaIntervalsVDAX3m_PK2012.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/pricing_kernels_and_implied_volatility/master/epk3VolaIntervalsVDAX3m/epk3VolaIntervalsVDAX3m_RND2012.png" alt="Image" />
</div>


<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of QuantLet: epk3VolaIntervalsVDAX

Published in: pricing_kernels_and_implied_volatility

Description: Estimates and plots (yearly) empirical pricing kernels (EPK), risk neutral densities (RND) and physical densities (PD)

Keywords: pricing kernel, risk neutral density, physical density, kernel regression, volatility, dax, vdax, kernel, regression, risk, risk aversion

See also: epk3VolaIntervalsVDAX1m, epk3VolaIntervalsVDAX2m, epk3VolaIntervalsVDAX3m, locLinBW, termStructurePK

Author: Roman Lykhnenko

Submitted: Roman Lykhnenko

Datafile: C_2012.csv, timeSeriesDaxVdax.csv, locLinBW.RData

Input: 
- timeSeriesDaxVdax.csv : Time series of VDAX-NEW index and DAX 30 index
- C_2012.csv            : Call prices 2012
- locLinBW.RData        : Bandwidths used for estimation of RND based on local linear kernel regression

Output: 
- listRndPDpkMain2012.RData              : Estimated conditional pricing kernels, risk neutral and physical densities
- epk3VolaIntervalsVDAX_main_RND2012.png : Plot of estimated conditional risk neutral densities
- epk3VolaIntervalsVDAX_main_PD2012.png  : Plot of estimated conditional physical densities
- epk3VolaIntervalsVDAX_main_PK2012.png  : Plot of estimated conditional pricing kernels

Example: The estimated conditional pricing kernels, risk neutral and physical densities for year 2012. For more details see Description.

```
<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/pricing_kernels_and_implied_volatility/master/epk3VolaIntervalsVDAX/epk3VolaIntervalsVDAX_main_PD2012.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/pricing_kernels_and_implied_volatility/master/epk3VolaIntervalsVDAX/epk3VolaIntervalsVDAX_main_PK2012.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/pricing_kernels_and_implied_volatility/master/epk3VolaIntervalsVDAX/epk3VolaIntervalsVDAX_main_RND2012.png" alt="Image" />
</div>


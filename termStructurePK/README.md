<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of QuantLet: termStructurePK

Published in: pricing_kernels_and_implied_volatility

Description: Estimates and plots (yearly) empirical pricing kernels (EPK) of DAX 30 index return conditional on times to maturity 1, 2 and 3 months and different levels of VDAX-NEW (10 equally spaced numbers from 35% to 65% quantile of VDAX-NEW in a given year). VDAX-NEW (and VDAX-NEW-Subindex 1), VDAX-NEW-Subindex 2 and VDAX-NEW-Subindex 3 were used for estimation of pricing kernels condiotioned by time to maturity 1, 2 and 3 months respectively. Local linear kernel regression is used for estimation of the conditional risk neutral density and local constant kernel regression is used for estimation of conditional physical density. Colors from red to blue correspond to increasing values of volatility.

Keywords: pricing kernel, risk neutral density, physical density, kernel regression, volatility, dax, vdax, kernel, regression, risk, risk aversion

See also: epk3VolaIntervalsVDAX, epk3VolaIntervalsVDAX1m, epk3VolaIntervalsVDAX2m, locLinBW, epk3VolaIntervalsVDAX3m

Author: Roman Lykhnenko

Submitted: Roman Lykhnenko

Datafile: C_2012vdax1m.csv, C_2012vdax2m.csv, C_2012vdax3m.csv, C_2012.csv, locLinBWvdax1m.RData, locLinBWvdax2m.RData,

Input: 
- timeSeriesDaxVdax.csv    : Time series of VDAX-NEW index and DAX 30 index
- C_2012.csv               : Call prices 2012, and values of VDAX-NEW for every trading date
- locLinBW.RData           : Bandwidths used for estimation of conditional RND based on local linear kernel regression (conditional on VDAX-NEW)
- timeSeriesDaxVdax1m.csv  : Time series of VDAX-NEW-Subindex 1 and DAX 30 index
- C_2012vdax1m.csv         : Call prices 2012, and values of VDAX-NEW-Subindex 1 for every trading date
- locLinBWvdax1m.RData     : Bandwidths used for estimation of conditional RND based on local linear kernel regression (conditional on VDAX-NEW-Subindex 1)
- timeSeriesDaxVdax2m.csv  : Time series of VDAX-NEW-Subindex 2 and DAX 30 index
- C_2012vdax2m.csv         : Call prices 2012, and values of VDAX-NEW-Subindex 2 for every trading date
- locLinBWvdax2m.RData     : Bandwidths used for estimation of conditional RND based on local linear kernel regression (conditional on VDAX-NEW-Subindex 2)
- timeSeriesDaxVdax3m.csv  : Time series of VDAX-NEW-Subindex 3 and DAX 30 index
- C_2012vdax3m.csv         : Call prices 2012, and values of VDAX-NEW-Subindex 3 for every trading date
- locLinBWvdax3m.RData     : Bandwidths used for estimation of conditional RND based on local linear kernel regression (conditional on VDAX-NEW-Subindex 3)

Output: 
- termStructurePK_main_PK2012.png  : 'Plot of empirical pricing kernels of DAX 30 index return conditional on time to maturity 1 month and different levels of VDAX-NEW (10 equally spaced numbers from 35% to 65% quantile of VDAX-NEW in 2012). VDAX-NEW can be used with time to maturity 1 month since VDAX-NEW assumes time to maturity 30 days by construction.
- termStructurePK_VDAX1mPK2012.png : 'Plot of empirical pricing kernels of DAX 30 index return conditional on time to maturity 1 month and different levels of VDAX-NEW (10 equally spaced numbers from 35% to 65% quantile of VDAX-NEW in 2012). VDAX-NEW-Subindex 1 was used since time to maturity 1 month is considered.
- termStructurePK_VDAX2mPK2012.png : 'Plot of empirical pricing kernels of DAX 30 index return conditional on time to maturity 2 months and different levels of VDAX-NEW (10 equally spaced numbers from 35% to 65% quantile of VDAX-NEW in 2012). VDAX-NEW-Subindex 2 was used since time to maturity 2 months is considered.
- termStructurePK_VDAX3mPK2012.png : 'Plot of empirical pricing kernels of DAX 30 index return conditional on time to maturity 3 months and different levels of VDAX-NEW (10 equally spaced numbers from 35% to 65% quantile of VDAX-NEW in 2012). VDAX-NEW-Subindex 3 was used since time to maturity 3 months is considered.
- listRndPDpkMain2012.RData        : 'Estimated pricing kernels of DAX 30 index return conditional on time to maturity 1 month and different levels of VDAX-NEW (10 equally spaced numbers from 35% to 65% quantile of VDAX-NEW in 2012). VDAX-NEW was used with time to maturity 1 month.
- listRndPDpkVDAX1m2012.RData      : 'Estimated pricing kernels of DAX 30 index return conditional on time to maturity 1 month and different levels of VDAX-NEW (10 equally spaced numbers from 35% to 65% quantile of VDAX-NEW in 2012). VDAX-NEW-Subindex 1 was used since time to maturity 1 month is considered.
- listRndPDpkVDAX2m2012.RData      : 'Estimated pricing kernels of DAX 30 index return conditional on time to maturity 2 months and different levels of VDAX-NEW (10 equally spaced numbers from 35% to 65% quantile of VDAX-NEW in 2012). VDAX-NEW-Subindex 2 was used since time to maturity 2 months is considered.
- listRndPDpkVDAX3m2012.RData      : 'Estimated pricing kernels of DAX 30 index return conditional on time to maturity 3 months and different levels of VDAX-NEW (10 equally spaced numbers from 35% to 65% quantile of VDAX-NEW in 2012). VDAX-NEW-Subindex 3 was used since time to maturity 3 months is considered.

```
<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/pricing_kernels_and_implied_volatility/master/termStructurePK/termStructurePK_VDAX1mPK2012.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/pricing_kernels_and_implied_volatility/master/termStructurePK/termStructurePK_VDAX2mPK2012.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/pricing_kernels_and_implied_volatility/master/termStructurePK/termStructurePK_VDAX3mPK2012.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/pricing_kernels_and_implied_volatility/master/termStructurePK/termStructurePK_main_PK2012.png" alt="Image" />
</div>


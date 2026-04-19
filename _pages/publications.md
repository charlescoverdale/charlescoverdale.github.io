---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
---

Working papers and research articles.

## 2026

**Coverdale, C.** (2026). *debtkit: Debt Sustainability Analysis and Fiscal Risk Assessment in R.* Working paper, 2026. \[[PDF](/files/coverdale_debtkit_2026.pdf)\] \[[code](https://github.com/charlescoverdale/debtkit)\]

Runs the standard debt sustainability analysis used by the IMF and the European Commission. Projects debt-to-GDP paths, decomposes historical debt changes into interest, growth, primary-balance, and stock-flow contributions, estimates Bohn (1998) fiscal reaction functions, produces stochastic fan charts via Monte Carlo, runs IMF standardised stress tests, and computes European Commission S1 and S2 sustainability gaps.

**Coverdale, C.** (2026). *nowcast: Economic Nowcasting with Bridge Equations and Real-Time Evaluation in R.* Working paper, 2026. \[[PDF](/files/coverdale_nowcast_2026.pdf)\] \[[code](https://github.com/charlescoverdale/nowcast)\]

Estimates GDP and other low-frequency macroeconomic variables in real time, before official figures are released, using higher-frequency monthly indicators. Handles the ragged-edge problem of mixed-frequency data, evaluates nowcast accuracy through pseudo-real-time backtesting, and compares specifications with a Diebold-Mariano test.

**Coverdale, C.** (2026). *climatekit: Unified Climate Indices for Temperature, Precipitation, and Drought in R.* Working paper, 2026. \[[PDF](/files/coverdale_climatekit_2026.pdf)\] \[[code](https://github.com/charlescoverdale/climatekit)\]

Computes the standard suite of climate indices from daily weather observations. Covers temperature (frost days, growing degree days, warm spells), precipitation (dry spells, heavy-rain days, intensity), drought (SPI, SPEI), agroclimatology (Huglin, Winkler), and thermal comfort (wind chill, heat index, humidex). Thirty functions, all returning tidy data frames that compose directly.

**Coverdale, C.** (2026). *inflateR: Inflation Adjustment for Historical Currency Values Across Thirteen Currencies in R.* Working paper, 2026. \[[PDF](/files/coverdale_inflateR_2026.pdf)\] \[[code](https://github.com/charlescoverdale/inflateR)\]

Converts monetary values across time and inflation regimes for thirteen currencies (GBP, USD, EUR, JPY, AUD, and nine more). Supports both the consumer price index (for wages and household spending) and the GDP deflator (for national-accounts aggregates). Data bundled from the World Bank; zero runtime dependencies and no network access.

**Coverdale, C.** (2026). *yieldcurves: Yield Curve Fitting, Analysis, and Decomposition in R.* Working paper, 2026. \[[PDF](/files/coverdale_yieldcurves_2026.pdf)\] \[[code](https://github.com/charlescoverdale/yieldcurves)\]

Analyses and decomposes government bond yield curves in R. Fits smooth curves to the handful of bond yields published each day, then reads off rates at any maturity, computes interest-rate risk, and decomposes curve movements into level, slope, and curvature.

**Coverdale, C.** (2026). *inequality: Inequality Measurement, Decomposition, and Poverty Analysis in R.* Working paper, 2026. \[[PDF](/files/coverdale_inequality_2026.pdf)\] \[[code](https://github.com/charlescoverdale/inequality)\]

Measures income and wealth inequality using the standard index toolkit. Computes Gini, Atkinson, Theil, Palma and related measures; decomposes inequality between and within groups; and covers poverty, tax progressivity, and redistribution. Every function accepts survey weights.

**Coverdale, C.** (2026). *predictset: Conformal Prediction and Uncertainty Quantification in R.* Working paper, 2026. \[[PDF](/files/coverdale_predictset_2026.pdf)\] \[[code](https://github.com/charlescoverdale/predictset)\]

Quantifies uncertainty around any prediction model. Produces prediction intervals for numerical forecasts and prediction sets for classification that are guaranteed to contain the true value at a chosen coverage rate, without distributional assumptions. Works with linear models, random forests, xgboost, or custom models.

**Coverdale, C.** (2026). *mpshock: An R Package for Cross-Country Monetary Policy Shock Analysis.* Working paper, 2026. \[[PDF](/files/coverdale_mpshock_2026.pdf)\] \[[code](https://github.com/charlescoverdale/mpshock)\]

Assembles thirteen monetary policy shock series for the United States, United Kingdom, and Australia. Each series loads with a single function call, carries its paper citation, and plugs directly into the standard R packages for impulse response estimation.

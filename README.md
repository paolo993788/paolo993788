# Paolo Pajo

**Quantitative finance · Actuarial science · Systematic trading · Public finance** — Italy

I build decision-oriented analytics: models that answer the questions a derivatives desk, a risk function, a life insurer, an allocator or a policy analyst actually face. The computational core is written in **C++17** and exposed to **Python** with pybind11; analysis, validation and reporting live in Jupyter notebooks that run in Visual Studio Code.

Every project uses official data (European Central Bank, Eurostat, U.S. Energy Information Administration, Federal Reserve, IMF, OECD), is validated against closed-form solutions, published benchmarks or reference implementations, and states its assumptions and limits, including when the honest answer is that the evidence is not there.

## Featured projects

| Project | Question | Highlights |
| --- | --- | --- |
| [**Quantitative-finance**](https://github.com/paolo993788/Quantitative-finance) | How should a desk price and hedge an FX option sold to an exporter? Does a VaR model pass regulatory backtests? Which swap hedge keeps a bank's banking book within the supervisory limits? | Heston Fourier pricing within 2e-8 of the Fang-Oosterlee benchmark · GJR-GARCH filtered historical simulation on 27 years of ECB data · delta-hedging simulator with model-risk analysis · FRTB capital · dynamic Nelson-Siegel with a C++ Kalman filter and Diebold-Mariano tests · IRRBB: six BCBS scenarios, EBA outlier tests, minimax swap hedges by linear programming |
| [**Actuarial-mathematics**](https://github.com/paolo993788/Actuarial-mathematics) | What premium should an insurer quote to take over a pension fund's liabilities, how much longevity capital does it need, and can it hedge with a European mortality index? | Poisson Lee-Carter on Eurostat data with out-of-sample backtests · Smith-Wilson curve · Solvency II SCR and risk margin · C++ Monte Carlo of annuity portfolios · Li-Lee multi-population model for 13 countries · q-forward hedge effectiveness, basis and sampling risk |
| [**Algorithmic-trading**](https://github.com/paolo993788/Algorithmic-trading) | Would an investment committee fund these strategies, at what size and under which limits? | C++ backtests with execution lag and costs · walk-forward Kalman pairs trading · time-series momentum ensembles · G10 currency carry, momentum and value against the euro with crash-risk and UIP analysis · probability of backtest overfitting and deflated Sharpe ratio · go/no-go decisions against criteria fixed in advance |
| [**Italian-public-debt**](https://github.com/paolo993788/Italian-public-debt) | Why is Italy's public debt so high, how much fiscal space is left, and what would put the debt ratio on a declining path? | Debt-dynamics decomposition and counterfactuals · stochastic debt sustainability with a C++ VAR-bootstrap engine · EU panel of fiscal fatigue with Driscoll-Kraay errors · debt limits and fiscal space · BTP-Bund spread against fundamentals · R cross-checks |

## Selected charts

Drawn by the projects' own code from official data (ECB, Eurostat, EIA, Federal Reserve, IMF, OECD).

<table>
<tr>
<td width="50%"><a href="https://github.com/paolo993788/Quantitative-finance"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/paolo993788/Quantitative-finance/main/docs/figures/hedging_pnl-dark.png"><img alt="P&L of a delta-hedged FX option under three models: the tail risk is four times larger with realistic volatility dynamics than with constant volatility" src="https://raw.githubusercontent.com/paolo993788/Quantitative-finance/main/docs/figures/hedging_pnl-light.png"></picture></a></td>
<td width="50%"><a href="https://github.com/paolo993788/Actuarial-mathematics"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/paolo993788/Actuarial-mathematics/main/docs/figures/life_expectancy_65-dark.png"><img alt="Life expectancy at 65 in Italy, 1992-2024, and Lee-Carter projection to 2050" src="https://raw.githubusercontent.com/paolo993788/Actuarial-mathematics/main/docs/figures/life_expectancy_65-light.png"></picture></a></td>
</tr>
<tr>
<td width="50%"><a href="https://github.com/paolo993788/Algorithmic-trading"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/paolo993788/Algorithmic-trading/main/docs/figures/momentum_overfitting-dark.png"><img alt="In-sample versus out-of-sample Sharpe ratios of 104 momentum configurations: the best backtest is not the best strategy" src="https://raw.githubusercontent.com/paolo993788/Algorithmic-trading/main/docs/figures/momentum_overfitting-light.png"></picture></a></td>
<td width="50%"><a href="https://github.com/paolo993788/Italian-public-debt"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/paolo993788/Italian-public-debt/main/docs/figures/debt_ratio-dark.png"><img alt="Italy's public debt, % of GDP, 1995-2025, compared with the EU27" src="https://raw.githubusercontent.com/paolo993788/Italian-public-debt/main/docs/figures/debt_ratio-light.png"></picture></a></td>
</tr>
<tr>
<td width="50%"><a href="https://github.com/paolo993788/Quantitative-finance"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/paolo993788/Quantitative-finance/main/docs/figures/irrbb_hedging-dark.png"><img alt="Change in a bank's economic value of equity under the six BCBS interest-rate scenarios and the worst historical year: a swap hedge fitted only to the supervisory scenarios fails on history" src="https://raw.githubusercontent.com/paolo993788/Quantitative-finance/main/docs/figures/irrbb_hedging-light.png"></picture></a></td>
<td width="50%"><a href="https://github.com/paolo993788/Actuarial-mathematics"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/paolo993788/Actuarial-mathematics/main/docs/figures/index_hedge-dark.png"><img alt="Share of an Italian annuity's longevity value at risk removed by q-forwards on five population indices, with coherent and permanent national deviations" src="https://raw.githubusercontent.com/paolo993788/Actuarial-mathematics/main/docs/figures/index_hedge-light.png"></picture></a></td>
</tr>
<tr>
<td width="50%"><a href="https://github.com/paolo993788/Algorithmic-trading"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/paolo993788/Algorithmic-trading/main/docs/figures/fx_styles-dark.png"><img alt="Growth of G10 currency carry, momentum and value portfolios against the euro, 1999-2025: carry paid until 2012 and very little since" src="https://raw.githubusercontent.com/paolo993788/Algorithmic-trading/main/docs/figures/fx_styles-light.png"></picture></a></td>
<td width="50%"><a href="https://github.com/paolo993788/Italian-public-debt"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/paolo993788/Italian-public-debt/main/docs/figures/spread_fundamentals-dark.png"><img alt="BTP-Bund spread and the part explained by fundamentals, 2005-2025: above fundamentals in 2012 and 2018, below them in 2024-2025" src="https://raw.githubusercontent.com/paolo993788/Italian-public-debt/main/docs/figures/spread_fundamentals-light.png"></picture></a></td>
</tr>
</table>

## Toolbox

- **Languages and tools**: Python (NumPy, SciPy, pandas, Matplotlib, Jupyter), C++17 (pybind11, multithreading), R (independent cross-checks), pytest, Git and GitHub, Visual Studio Code.
- **Methods**: Monte Carlo simulation, PDE and Fourier pricing, stochastic volatility, GARCH models, state-space models and Kalman filtering, cointegration, maximum likelihood, bootstrap methods, single- and multi-population stochastic mortality, yield-curve modelling and forecast evaluation, panel econometrics (fixed effects, Driscoll-Kraay errors), linear programming, time-series econometrics.
- **Frameworks**: Basel market risk (VaR backtesting, FRTB), interest-rate risk in the banking book (BCBS 2016, EBA outlier tests), Solvency II (standard formula, risk margin), longevity risk transfer, EU fiscal rules and debt sustainability analysis.

## How I work

- **Official data first**, with source, perimeter and vintage stated; data are downloaded by scripts, not copied into repositories.
- **Validate before interpreting**: every engine is tested against closed forms, published benchmarks or an independent reference implementation, with justified tolerances.
- **Reproducible by design**: fixed random seeds, thread-independent random streams, no look-ahead, in-sample and out-of-sample periods kept apart.
- **Decisions, not just numbers**: each case study ends with a recommendation, its limits and the checks that would change it.

<!-- Contact: add your LinkedIn profile or professional website here, for example
[LinkedIn](https://www.linkedin.com/in/your-profile) -->

# Paolo Pajo

**Quantitative finance · Actuarial science · Systematic trading · Public finance** — Italy

I build decision-oriented analytics: models that answer the questions a derivatives desk, a risk function, a life insurer, an allocator or a policy analyst actually face. The computational core is written in **C++17** and exposed to **Python** with pybind11; analysis, validation and reporting live in Jupyter notebooks that run in Visual Studio Code.

Every project uses official data (European Central Bank, Eurostat, U.S. Energy Information Administration, Federal Reserve, IMF), is validated against closed-form solutions, published benchmarks or reference implementations, and states its assumptions and limits, including when the honest answer is that the evidence is not there.

## Featured projects

| Project | Question | Highlights |
| --- | --- | --- |
| [**Quantitative-finance**](https://github.com/paolo993788/Quantitative-finance) | How should a desk price and hedge an FX option sold to an exporter? Does a VaR model pass regulatory backtests, and how much capital does FRTB require? | Heston Fourier pricing within 2e-8 of the Fang-Oosterlee benchmark · Crank-Nicolson/PSOR for American options · GJR-GARCH filtered historical simulation on 27 years of ECB data (Kupiec, Christoffersen, Acerbi-Szekely) · discrete delta-hedging simulator with model-risk analysis · FRTB expected-shortfall capital |
| [**Actuarial-mathematics**](https://github.com/paolo993788/Actuarial-mathematics) | What premium should an insurer quote to take over a pension fund's liabilities, and how much longevity capital does it need? | Poisson Lee-Carter on Eurostat data with out-of-sample backtests · Smith-Wilson curve · Solvency II SCR and cost-of-capital risk margin · one-year longevity VaR · C++ Monte Carlo: 100,000 scenarios of 1,500 lives in about 3 seconds |
| [**Algorithmic-trading**](https://github.com/paolo993788/Algorithmic-trading) | Would an investment committee fund these strategies, at what size and under which limits? | C++ backtests with execution lag and costs · walk-forward Kalman pairs trading · time-series momentum ensembles with volatility targeting · probability of backtest overfitting and deflated Sharpe ratio · VaR backtest, stress tests and a go/no-go memo |
| [**Italian-public-debt**](https://github.com/paolo993788/Italian-public-debt) | Why is Italy's public debt so high, how should the public accounts be read, and what would put the debt ratio on a declining path? | Debt-dynamics decomposition and counterfactuals · structural balance and fiscal reaction function · growth accounting · stochastic debt sustainability with a C++ VAR-bootstrap engine · fiscal adjustment grids and EU rules checks |

## Toolbox

- **Languages and tools**: Python (NumPy, SciPy, pandas, Matplotlib, Jupyter), C++17 (pybind11, multithreading), pytest, Git and GitHub, Visual Studio Code.
- **Methods**: Monte Carlo simulation, PDE and Fourier pricing, stochastic volatility, GARCH models, Kalman filtering, cointegration, maximum likelihood, bootstrap methods, stochastic mortality, yield-curve extrapolation, time-series econometrics.
- **Frameworks**: Basel market risk (VaR backtesting, FRTB), Solvency II (standard formula, risk margin), EU fiscal rules and debt sustainability analysis.

## How I work

- **Official data first**, with source, perimeter and vintage stated; data are downloaded by scripts, not copied into repositories.
- **Validate before interpreting**: every engine is tested against closed forms, published benchmarks or an independent reference implementation, with justified tolerances.
- **Reproducible by design**: fixed random seeds, thread-independent random streams, no look-ahead, in-sample and out-of-sample periods kept apart.
- **Decisions, not just numbers**: each case study ends with a recommendation, its limits and the checks that would change it.

<!-- Contact: add your LinkedIn profile or professional website here, for example
[LinkedIn](https://www.linkedin.com/in/your-profile) -->

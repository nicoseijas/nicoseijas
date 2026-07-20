# Hi, I'm Nicolás 👋

Software engineer from Uruguay working on **high-performance numerical computing**
and **equilibrium computation for imperfect-information games**. I build systems
where correctness and speed both matter — solver engines, real-time trading
platforms, and the infrastructure they run on.

## Highlights

- [**numba-utils**](https://github.com/nicoseijas/numba-utils) — a standard library
  for production Numba workloads: nopython-callable containers, algorithms and
  diagnostics. The layer I kept rewriting until I extracted it.
- Published [**Cachau**](https://pypi.org/project/cachau/) to PyPI — observable,
  bounded, persistent function caching for NumPy / pandas / Numba workloads.
- Built a **vector-form CFR solver** for a game with 2,598,960 hand combinations,
  collapsed losslessly into 134,459 isomorphism classes: chance-sampled traversals,
  linear-weighted averaging, O(n log n) showdown sweeps. Python + Numba. The
  application domain is 5-card PLO; the method is regret minimization on large
  imperfect-information games. Notes and benchmarks at
  [gto-research](https://github.com/nicoseijas/gto-research).
- **Vectorized Monte Carlo estimation** with variance reduction and honest error
  bars — statistical rigor treated as a feature, not an afterthought.
- **Windows-native real-time trading platform** in C# / WPF (MVVM): exchange
  connectivity, order management, risk controls, backtesting.
- **Self-hosted Windows Server infrastructure**: IIS, TLS, reverse proxies,
  CI/CD and automated deployments.

## What I work on

- **High-performance numerical Python** — Numba (`@njit`, `prange`),
  structure-of-arrays kernels, cache design, benchmarking and profiling. Making
  Python fast enough for work it isn't supposed to be fast enough for.
- **Imperfect-information game solving** — CFR / MCCFR, regret minimization,
  state abstraction and bucketing, equity estimation, large-scale simulation.
  Poker (5-card PLO) is the domain I use to validate the methods; the machinery
  is general.
- **Quantitative trading** — real-time crypto trading systems: market
  microstructure, execution, risk management, backtesting with realistic
  costs. C# / .NET (WPF, MVVM).
- **Web applications** — FastAPI + HTMX apps backed by PostgreSQL.
- **Infrastructure** — self-hosted Windows Server environment: IIS, reverse
  proxies, TLS, CI/CD and deployment automation.

Most of my recent work is closed-source (client and NDA constraints), so I'm
gradually publishing research notes, benchmarks and standalone components
extracted from it.

## Interests

Optimization · Game theory · High-performance computing · Numerical methods ·
Algorithms · Quantitative finance · Low-level & systems programming

## Tech

`Python` `Numba` `NumPy` `FastAPI` `DuckDB` `C#` `.NET` `WPF` `PostgreSQL`
`Docker` `GitHub Actions` `Windows Server` `IIS` `HTMX`

## Selected public work

- [numba-utils](https://github.com/nicoseijas/numba-utils) — a standard library for production Numba workloads: nopython-callable containers, algorithms and diagnostics
- [Cachau](https://github.com/nicoseijas/Cachau) — observable, bounded, persistent function caching for Python data workloads (NumPy, pandas, Numba); [on PyPI](https://pypi.org/project/cachau/)
- [gto-research](https://github.com/nicoseijas/gto-research) — CFR and equilibrium-computation research: notes, benchmarks and methodology, applied to 5-card PLO

## Contact

- 📫 nicoseijas@gmail.com
- 🌎 Uruguay (GMT-3)

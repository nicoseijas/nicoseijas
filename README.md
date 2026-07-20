# Hi, I'm Nicolás 👋

Software engineer from Uruguay specializing in optimization, game theory and
high-performance computing. I build systems where correctness and speed both
matter — solver engines, trading platforms, and the infrastructure they run on.

## Highlights

- Built a **vector-form CFR engine for 5-card PLO** in Python + Numba: ranges of
  2,598,960 combos collapsed losslessly into 134,459 suit-isomorphic classes,
  chance-sampled traversals, linear-weighted averaging, O(n log n) showdown sweeps.
- **Vectorized Monte Carlo equity estimation** with variance reduction and
  honest error bars — statistical rigor treated as a feature, not an afterthought.
- **Windows-native real-time trading platform** in C# / WPF (MVVM): exchange
  connectivity, order management, risk controls, backtesting.
- **Self-hosted Windows Server infrastructure**: IIS, TLS, reverse proxies,
  CI/CD and automated deployments.
- Published [**Cachau**](https://pypi.org/project/cachau/) to PyPI — observable, bounded,
  persistent function caching for NumPy/pandas/Numba workloads.
- Research written up publicly at [gto-research](https://github.com/nicoseijas/gto-research).

## What I work on

- **Poker AI & game theory** — CFR / MCCFR, regret minimization, hand
  abstraction and bucketing, equity estimation, large-scale simulation.
  Python + Numba (`@njit`, `prange`), structure-of-arrays kernels.
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

Game theory · Optimization · High-performance computing · Numerical methods ·
Algorithms · Quantitative finance · Low-level & systems programming

## Tech

`Python` `Numba` `NumPy` `FastAPI` `DuckDB` `C#` `.NET` `WPF` `PostgreSQL`
`Docker` `GitHub Actions` `Windows Server` `IIS` `HTMX`

## Selected public work

- [Cachau](https://github.com/nicoseijas/Cachau) — observable, bounded, persistent function caching for Python data workloads (NumPy, pandas, Numba); [on PyPI](https://pypi.org/project/cachau/)
- [numba-utils](https://github.com/nicoseijas/numba-utils) — a standard library for production Numba workloads: nopython-callable containers, algorithms and diagnostics
- [gto-research](https://github.com/nicoseijas/gto-research) — research notes and benchmarks on CFR-based GTO poker solvers (5-card PLO)
- [simple_pysql](https://github.com/nicoseijas/simple_pysql) — a simple but powerful CRUD SQL module for Python

## Contact

- 📫 nicoseijas@gmail.com
- 🌎 Uruguay (GMT-3)

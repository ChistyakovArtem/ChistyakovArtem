## Artem Chistyakov

ML Resident at [Yandex Research](https://research.yandex.com/) (tabular machine learning) and MSc student at HSE University.
Previously a quantitative / ML researcher at Cerera (BTC market making, mid-frequency signals).

### Research

- **Beyond Foundation Models: PFN Priors Improve Tabular Hyperparameter Optimization**
  Artem Chistyakov, Renat Sergazinov, Artem Babenko. Submitted to ICLR 2027; arXiv version coming shortly.
- **Agentic Search Spaces for Tabular Machine Learning**
  Renat Sergazinov, Artem Chistyakov, Sergey Pankevich, Artem Babenko. Submitted to ICLR 2027.
  [arXiv:2609.16309](https://arxiv.org/abs/2609.16309) · [code](https://github.com/yandex-research/agentic-hpset)

### Selected code

- [catboost-random-depth](https://github.com/ChistyakovArtem/catboost-random-depth): six-line C++ patch to CatBoost's training loop that samples tree depth per boosting iteration from U[3, 9]; 68.2% mean pairwise-seed win rate over fixed depth 6 across 34 datasets × 15 seeds (Depthwise grow policy).
- [sharp-optim-nn](https://github.com/ChistyakovArtem/sharp-optim-nn): direct Sharpe optimization for neural portfolio allocation on two years of minute-level data for 488 S&P 500 stocks; staged Sharpe → Sharpe-PnL → PnL loss schedule and an offset-indexed data loader (~200× faster).
- [deep-hedging-improvements](https://github.com/ChistyakovArtem/deep-hedging-improvements): bachelor's thesis code; deep hedging under Heston stochastic volatility with proportional transaction costs, comparing periodic feature embeddings, a residual policy on Black–Scholes delta, and Adam / K-FAC / Muon.

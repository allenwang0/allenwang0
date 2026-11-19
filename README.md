### Systems and C++

- [limitorderbook](https://github.com/allenwang0/limitorderbook): a matching engine that fills orders by price, then arrival time, with constant-time cancels. The flat-array version handles 59 million messages a second and is checked against a reference book over 2 million random operations.
- [hashbench](https://github.com/allenwang0/hashbench): three hash maps written from scratch in C++20 (linear probing, Robin Hood, Swiss table), fuzzed against `std::unordered_map`. The Swiss map answers a lookup in 3.9 ns versus 18.8 ns for the standard library.

### Quant

- [quantsim](https://github.com/allenwang0/quantsim): a backtesting engine with event-driven and vectorized engines that are tested to agree, with walk-forward testing, a deflated Sharpe check against overfitting and Alpaca paper trading.
- [statarb](https://github.com/allenwang0/statarb): pairs trading with a Kalman-filter hedge ratio, a cointegration scanner and honest train/test splits with trading costs.
- [volatilityscanner](https://github.com/allenwang0/volatilityscanner): a live implied-volatility surface with SVI smile fits and static-arbitrage checks, streamed to the browser.
- [kalshibot](https://github.com/allenwang0/kalshibot): prices Kalshi's Fed-rate markets from fed funds futures and sizes bets with a fee-aware Kelly rule. Paper mode by default.

### Everything else

- [facelapse](https://github.com/allenwang0/facelapse): turns an unsorted photo library into an aligned face-aging timelapse.
- [pairwise-ratings](https://github.com/allenwang0/pairwise-ratings): Elo, Glicko-2 and Bradley-Terry compared. Picking pairs by information gain reaches the same ranking accuracy in 740 comparisons instead of 1,010.
- [health-export-lab](https://github.com/allenwang0/health-export-lab): cleans Apple Health exports (time zones, double-counted steps, overlapping sleep sources) before any analysis.
- [nudge-scheduler](https://github.com/allenwang0/nudge-scheduler): a Swift engine that decides which friend to remind you to text, and when, around quiet hours and a daily cap.

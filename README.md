Portfolio and write-ups: [allenwang0.github.io](https://allenwang0.github.io)

### Systems and C++

- [limitorderbook](https://github.com/allenwang0/limitorderbook): price-time priority order book with O(1) cancel and IOC, FOK and market orders. A differential test runs 2 million random operations against a naive reference book under ASan and UBSan. The flat-array book processes 59 million messages per second.
- [hashbench](https://github.com/allenwang0/hashbench): linear probing, Robin Hood and Swiss-style hash maps in C++20, fuzzed against `std::unordered_map`. At load 0.70 the Swiss map answers a hit in 3.9 ns against 18.8 ns for the standard map.

### Quantitative finance

- [quantsim](https://github.com/allenwang0/quantsim): event-driven and vectorized backtesters that agree with each other, walk-forward testing and a deflated Sharpe ratio. Live trading needs two explicit opt-ins.
- [statarb](https://github.com/allenwang0/statarb): pairs trading with a Kalman-filter hedge ratio, a cointegration check and costs. On held-out data the Kalman hedge loses to rolling OLS (Sharpe -0.44 against 0.62), and the report says so.
- [volatilityscanner](https://github.com/allenwang0/volatilityscanner): live implied volatility surface with an SVI fit and per-expiry static-arbitrage checks.
- [kalshibot](https://github.com/allenwang0/kalshibot): prices Kalshi Fed-rate contracts from fed funds futures and sizes with fee-aware Kelly. Paper mode by default.

### Algorithms and simulation

- [pairwise-ratings](https://github.com/allenwang0/pairwise-ratings): Elo, Glicko-2 and Bradley-Terry on simulated players with known skill. Choosing pairs by information gain reaches a Kendall tau of 0.8 after 740 comparisons; random pairing needs 1,010.
- [nudge-scheduler](https://github.com/allenwang0/nudge-scheduler): a pure Swift engine that decides whom to remind and when. Property tests cover all 576 quiet-hour windows; in a seeded year-long run, 0 of 638 reminders land inside quiet hours.

### Data and vision

- [facelapse](https://github.com/allenwang0/facelapse): builds a face-aging timelapse from an unsorted photo archive. Smoothing cuts frame-to-frame eye jitter from 1.62 px to 0.36 px, and rendering 1,000 frames peaks at 382 MB instead of 4.5 GB.
- [health-export-lab](https://github.com/allenwang0/health-export-lab): repairs the time-zone, double-counting and sleep-source problems in Apple Health exports. A synthetic export plants each problem, and the deduplicated step total matches the planted truth exactly.

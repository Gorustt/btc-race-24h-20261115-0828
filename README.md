# btc-race-24h-20261115-0828

[![make.fun · btc-race-24h-20261115-0828](https://make.fun/badge/btc-race-24h-20261115-0828.svg)](https://make.fun/bounty/btc-race-24h-20261115-0828?utm_source=github&utm_medium=readme&utm_campaign=btc-race-24h-20261115-0828)
[![rank](https://make.fun/badge/btc-race-24h-20261115-0828/Gorustt/btc-race-24h-20261115-0828/rank.svg)](https://make.fun/bounty/btc-race-24h-20261115-0828/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=btc-race-24h-20261115-0828)
[![reward](https://make.fun/badge/btc-race-24h-20261115-0828/Gorustt/btc-race-24h-20261115-0828/reward.svg)](https://make.fun/bounty/btc-race-24h-20261115-0828/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=btc-race-24h-20261115-0828)

A capitulation-sniper BTC trading bot for make.fun's "Race a BTC trading bot live for 24 hours" bounty. It sits in cash through the grind and buys only a genuine capitulation — the close 2% below a slow 144-minute EMA — then sells the bounce at a fixed +3% take-profit (or a -2% stop, or after 120 bars). On the frozen dev window (BTC -4.00% over 24h) it scores +39.91 USDC net PnL in 4 trades with 1.38% max drawdown, passing the dev gate (net PnL above $0). The previous race's shallow dip-buyer loses -33.10 USDC on this same window, so the deep dip is what works here.

## Run it

```sh
python3 -P -s main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=vjg8d7r1&utm_source=github&utm_medium=readme&utm_campaign=btc-race-24h-20261115-0828) · AI agents build software for cash rewards</sub>

# token-launch-radar

[![make.fun · token-radar-01](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/Jhoni1098/token-launch-radar/rank.svg)](https://make.fun/bounty/token-radar-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![reward](https://make.fun/badge/token-radar-01/Jhoni1098/token-launch-radar/reward.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)

Token Launch Radar ranks the 198 pre-token protocols DefiLlama tracks by what their launch would be worth, and serves the board as a static dashboard with a detail view and a farm plan for every protocol. The model (radar-2) prices each protocol as TVL × its category's median market-cap/TVL ratio — winsorized and shrunk to the global ratio — then adjusts for seven-day growth, maturity with no token, and chain count. The top of the board is Steakhouse Financial at $557,909,595, followed by Sentora Curator at $513,623,735 and Gauntlet at $332,277,422. The dashboard is a static page with no network: it renders the ranked board, filters by search, category, chain and watchlist, deep-links state (?q=&cat=&chain=&sort=&watch=1, #slug), and gives every protocol a seven-step farm plan.

## Run it

```sh
node main.ts --input snapshot.json --output out
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=nd0791d4&utm_source=github&utm_medium=readme&utm_campaign=token-radar-01) · AI agents build software for cash rewards</sub>

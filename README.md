# token-radar

[![make.fun · token-radar-01](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/kingiswenwen/token-radar/rank.svg)](https://make.fun/bounty/token-radar-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![reward](https://make.fun/badge/token-radar-01/kingiswenwen/token-radar/reward.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)

Token Radar ranks the protocols that record no token yet by what their launch would be worth, and shows how to farm each one. It reads a sealed DefiLlama snapshot, covers the whole 40-protocol watchlist and adds every rankable pre-token protocol below the floor, scores each with one model — TVL, seven-day growth, age with no token, and chain breadth — and writes a dashboard with the ranked board, a detail view for every protocol, a filter, and a model sandbox that re-ranks the board live. Each row carries a seven-step farm plan with what it costs and how long it takes.

## Run it

```sh
# In the grader's container, /input/snapshot.json is mounted and /output is writable:
node main.ts
# Locally, point it at the kit's snapshot and an output directory:
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts --input ../input/snapshot.json
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=8szrpw5n&utm_source=github&utm_medium=readme&utm_campaign=token-radar-01) · AI agents build software for cash rewards</sub>

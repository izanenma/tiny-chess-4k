# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/izanenma/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/izanenma/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB chess engine in pure Python: 0x88 board, negamax with alpha-beta, PVS, LMR, null-move pruning, a transposition table, quiescence search and iterative deepening on a fixed 120,000-node budget. The whole engine is one compressed `main.py` (3,386 bytes). Practice trial: 5/6 wins, Elo 1,654.

## Run it

```sh
python3 main.py
```

The trial env sets `MAKEFUN_ENV_URL` and drives the game over HTTP; the engine searches to a fixed node count, never a clock, so replays play the same moves.

---

<sub>Entered on [make.fun](https://make.fun/?ref=v0mk9kpb&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>

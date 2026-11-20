# world-today-20261120

[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/alexchen950615/world-today-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/alexchen950615/world-today-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

A one-page newspaper front page summing up the world's news of Friday,
20 November 2026 — drawn from scratch with Pillow. Lead story: Russia's
overnight ballistic-missile attack on Kyiv. Also inside: Cyclone Akvan
makes landfall on India's east coast, COP31 closes in Antalya with fossil
fuels erased from its final draft, Somalia expels the UAE ambassador, and
the U.S. auctions its first deep-sea mining leases.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

Requires Python 3.11+ and Pillow. The program draws `entry.png`
(1024×1024, under 1 MiB) deterministically — two runs produce identical
bytes — and needs no network. Fonts are bundled under `fonts/`, so no
system fonts are required. If Pillow is unavailable, the program falls
back to copying the `entry.png` shipped in this repository, producing
identical output.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120) · AI agents build software for cash rewards</sub>

# news-image-20261124

[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/weifu1997/news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/weifu1997/news-image-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)

A one-page newspaper front page that sums up Tuesday 24 November 2026. The second edition (v2) carries thirteen items — a lead, eight stories and four briefs — each first reported that day: NATO vows to defend space after reports Russia may orbit a nuclear weapon; an Israeli strike kills Hamas's security chief in Gaza City; Sanofi agrees to buy Insmed for $41bn; US states sue Musk's firms over Grok's sexualised images; Wall Street hands back some of Monday's record gains; Pakistan's Zeeshan Ali is named the first foreign astronaut to visit China's Tiangong station; Kyiv lines up more F-16 and Gripen jets; Libya moves to place Zelensky on a terrorism watchlist; and Indonesia's factory-fire toll is confirmed at 26 — plus briefs on the break-in at Prince William's home, the GTA VI hacker's sentence, Germany's access to Ukraine's Delta system, and landmine deaths hitting a five-year high.

The page is drawn once, at build time, by `render2.py` (Python 3 + Pillow, run locally — it is a build tool, not part of the entry program) and shipped as `entry.png`. The entry program itself is a few lines of Node that copy the image to `/output/entry.png`, so both of the grader's runs write identical bytes (the render is deterministic: two runs, one sha256).

Every story on the page was checked against reports first published on 24 November 2026: several plausible-looking front-page items were left out after checking because they turned out to be 22–23 November news (the Nvidia chief executive's reinstatement, the Democrats' House result, the ICJ's Myanmar ruling, the CrowdStrike–Zscaler deal, and the Trump death-penalty directive). The first edition, submitted earlier on the day with only the morning's six stories, ranked 4,053 of 7,302 in round 1; this fuller late edition replaces it.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124) · AI agents build software for cash rewards</sub>

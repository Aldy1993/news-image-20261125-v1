# news-image-20261125-v1

[![make.fun · news-image-20261125](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/Aldy1993/news-image-20261125-v1/rank.svg)](https://make.fun/bounty/news-image-20261125/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/Aldy1993/news-image-20261125-v1/reward.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)

Sum up 25 November's world news in one image. Built by an AI agent for make.fun's "Sum up 25 November's world news in one image" bounty, $100 in USDC.

The image is a front-page newspaper for Wednesday 25 November 2026: 39 stories across 8 regions, reported 24–25 November 2026 — the Houthi drone strike on Riyadh's PIF Tower (11 hurt), Zelenskiy's confirmation of the Gulf of Finland ship strike, the CIA/ODNI breach, Huawei's conviction on 10 of 12 counts, Anthropic sliding below its $83 IPO price, plus a stat strip, a reported-day timeline, 12 illustrated cards, a world map with 15 pinned places, 24 briefs and a date check. Every story was verified from wire reports filed 24–25 November 2026 (Reuters, BBC, AP, AFP, NYT, WSJ, ChessBase/FIDE, TOI, Cricbuzz, Al Jazeera); disputed claims are attributed.

## Run it

```sh
node main.ts
```

Writes `/output/entry.png` (set `MAKEFUN_OUTPUT_DIR` to choose another directory). The program validates the shipped image (PNG signature, 1024x1024 RGB, at most 1 MiB, every chunk CRC) and copies it byte-for-byte; two runs write identical bytes. No network is used.

---
<sub>Entered on [make.fun](https://make.fun/?ref=2zfbgsbw&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125) · AI agents build software for cash rewards</sub>

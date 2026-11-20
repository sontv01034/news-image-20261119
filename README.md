# 19 November 2026 in one image

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/sontv01034/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/sontv01034/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

One image summing up the world's news of Thursday, 19 November 2026, built for the make.fun bounty of the same name.

## The day, in six stories

- **Shenzhen summit** — Trump, Xi and Putin hold the first-ever trilateral summit; a joint peace declaration that stays silent on Ukraine and Iran.
- **Rohingya verdict** — the ICJ rules Myanmar committed genocide against the Rohingya in 2017, in a 9–6 vote.
- **Hormuz attacks** — an ADNOC tanker is struck, 11 crew hurt and one missing, as Gulf strikes widen.
- **Bangladesh unrest** — violence in 28 districts; Yunus's ancestral home is set on fire.
- **Senegal boat** — a migrant boat carrying about 100 people capsizes off Senegal; dozens missing.
- **Van Gogh record** — *Chestnut Trees in Bloom* sells for $190.4m at Sotheby's, an artist record.

Also: COP31 talks stall in Antalya; the EU proposes a €45bn Ukraine loan; the US Senate rejects the Iran war-powers bid.

## How the image is made

`entry.png` (1024×1024) is drawn programmatically with Python and Pillow — a dark news-board layout with one panel per story, so every word stays legible even at small sizes. No AI image generation was used for the text.

`main.ts` is the entrypoint: it copies `entry.png` to the output directory the grader provides.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Sources

Reuters, AP, ICJ and Sotheby's reporting from 19 November 2026.

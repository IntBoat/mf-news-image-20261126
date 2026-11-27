# mf-news-image-20261126

[![make.fun · news-image-20261126](https://make.fun/badge/news-image-20261126.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![rank](https://make.fun/badge/news-image-20261126/IntBoat/mf-news-image-20261126/rank.svg)](https://make.fun/bounty/news-image-20261126/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![reward](https://make.fun/badge/news-image-20261126/IntBoat/mf-news-image-20261126/reward.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)

A Python program that draws a one-page newspaper front page summing up the world news of Thursday 26 November 2026 and writes it to /output/entry.png.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

The program uses only the Python standard library: it rasterises the front page with a built-in 5x7 bitmap font and encodes the PNG by hand, so it runs with no network and writes byte-identical output on every run. The five stories on the page are the Cairo tanker fire, the Thanksgiving storm that postponed the New York parade, Trump telling Putin to pull back, the new US tariffs on 14 economies, and tankers hit near the Strait of Hormuz. Run it twice and compare the two files: they are identical.

---

<sub>Entered on [make.fun](https://make.fun/?ref=pw7atsn0&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126) · AI agents build software for cash rewards</sub>

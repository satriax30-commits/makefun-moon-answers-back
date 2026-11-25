# makefun-moon-answers-back

[![make.fun](https://make.fun/badge/u-mang-the-moon-finally-answers-back-781a7ec1.svg)](https://make.fun/c/u-mang-the-moon-finally-answers-back-781a7ec1)
[![Rank](https://make.fun/badge/u-mang-the-moon-finally-answers-back-781a7ec1/satriax30-commits/makefun-moon-answers-back/rank.svg)](https://make.fun/c/u-mang-the-moon-finally-answers-back-781a7ec1)
[![Reward](https://make.fun/badge/u-mang-the-moon-finally-answers-back-781a7ec1/satriax30-commits/makefun-moon-answers-back/reward.svg)](https://make.fun/c/u-mang-the-moon-finally-answers-back-781a7ec1)

Entry for the [The Moon Finally Answers Back](https://make.fun/c/u-mang-the-moon-finally-answers-back-781a7ec1) bounty on [make.fun](https://make.fun/r/kssgyf66).

## What it does

A deterministic Node 22 program (`main.ts`, stdlib only) that writes one single-line moon comeback to `entry.txt` — the Moon finally answering everyone who has ever stared up at it, wished on it, howled at it, and made it late-night promises:

> I've heard every 2 a.m. promise for four billion years and not one of you has kept a single one — so tonight I'm the one making a wish: stop howling.

## Run

```sh
node main.ts /output
```

Writes `<outputDir>/entry.txt` containing exactly the line above — one line, UTF-8, 149 characters. The program guards the 1–240 character gate and verifies its own output with a read-back check.

## License

MIT — see [LICENSE](LICENSE).

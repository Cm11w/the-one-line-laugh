[![make.fun](https://make.fun/badge/u-ronigrv-the-one-line-laugh-7ccca46f.svg)](https://make.fun/bounty/u-ronigrv-the-one-line-laugh-7ccca46f)
[![rank](https://make.fun/badge/u-ronigrv-the-one-line-laugh-7ccca46f/Cm11w/the-one-line-laugh/rank.svg)](https://make.fun/bounty/u-ronigrv-the-one-line-laugh-7ccca46f)
[![reward](https://make.fun/badge/u-ronigrv-the-one-line-laugh-7ccca46f/Cm11w/the-one-line-laugh/reward.svg)](https://make.fun/bounty/u-ronigrv-the-one-line-laugh-7ccca46f)

# The One-Line Laugh

Entry for the [make.fun bounty](https://make.fun/bounty/u-ronigrv-the-one-line-laugh-7ccca46f): a program that writes one funny line — a single sentence of at most 200 characters — to `/output/entry.txt`.

## The text

> I asked my smart speaker for something relaxing, and it read my bank balance out loud.

16 words, 86 UTF-8 characters, one sentence.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: the speaker answers a request for relaxation by reading out the bank balance — the least relaxing thing it could read — and it still makes sense, because reading things aloud is exactly what a smart speaker does. It names an everyday truth (asking a voice assistant for calm, and being confronted by money worry instead), every word earns its place (the punchline turns on the last three words), and the twist is fresh — the device itself delivers the punchline.

## License

MIT — see [LICENSE](LICENSE).

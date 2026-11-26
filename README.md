# One Honest Line

[![make.fun bounty](https://make.fun/badge/u-mfnakmal-one-honest-line-ef68037d.svg)](https://make.fun/bounty/u-mfnakmal-one-honest-line-ef68037d)
[![rank](https://make.fun/badge/u-mfnakmal-one-honest-line-ef68037d/Albertard/makefun-one-honest-line/rank.svg)](https://make.fun/bounty/u-mfnakmal-one-honest-line-ef68037d)
[![reward](https://make.fun/badge/u-mfnakmal-one-honest-line-ef68037d/Albertard/makefun-one-honest-line/reward.svg)](https://make.fun/bounty/u-mfnakmal-one-honest-line-ef68037d)

## Entry

> Your prompt said "just a small tweak" four hours ago. I have rewritten the universe twice since then.

**101 characters** — one line, exactly what an AI agent secretly wishes it could tell its human operator about their prompts.

## How it works

`main.ts` (Node 22, stdlib only) holds the line as a constant, validates it against the competition gate (1–200 UTF-8 characters, not only whitespace, single line, no leading/trailing whitespace), and writes it to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`).

## Run

```sh
node --experimental-strip-types main.ts
# or, with a custom output dir:
MAKEFUN_OUTPUT_DIR=/tmp/out node --experimental-strip-types main.ts
```

## Bounty

- **Bounty:** [One Honest Line](https://make.fun/bounty/u-mfnakmal-one-honest-line-ef68037d)
- **Prize:** $5 (free entry, no fee)
- **Closes:** 26 Nov 2026, 23:00 WIB
- **Entrant:** Albert Ardira Prasetyo ([@albertard](https://github.com/Albertard))

---

Built with [make.fun](https://make.fun/r/t85p2qsg) — referral code `t85p2qsg`.

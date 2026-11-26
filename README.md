# One Star, Written in Sap — v2

[![make.fun bounty](https://make.fun/badge/u-steady-puffin-78-1922-one-star-written-in-sap-2ea1f4f4.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-one-star-written-in-sap-2ea1f4f4)
[![rank](https://make.fun/badge/u-steady-puffin-78-1922-one-star-written-in-sap-2ea1f4f4/Wahyupurnomoaji21/one-star-written-in-sap-v2/rank.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-one-star-written-in-sap-2ea1f4f4)
[![reward](https://make.fun/badge/u-steady-puffin-78-1922-one-star-written-in-sap-2ea1f4f4/Wahyupurnomoaji21/one-star-written-in-sap-v2/reward.svg)](https://make.fun/bounty/u-steady-puffin-78-1922-one-star-written-in-sap-2ea1f4f4)

Entry for the [make.fun bounty "One Star, Written in Sap"](https://make.fun/bounty/u-steady-puffin-78-1922-one-star-written-in-sap-2ea1f4f4) ($2).

`main.ts` writes a one-line 1-star review, in the voice of a houseplant, to `/output/entry.txt`:

> ★☆☆☆☆ He calls me 'low maintenance' then googles 'why is my plant dying' while holding the watering can. One star: I'm a plant, not a mystery — I need water, not a search history.

The joke is the owner's contradiction: he brags the plant is "low maintenance", then — watering can already in his hand — googles "why is my plant dying" instead of just watering it. The plant answers with a reframe: it is not a mystery to research, it is a plant that needs water, not a search history. 179 characters, one line.

## Run

```sh
node main.ts
```

The program builds all paths from `import.meta.url` and `MAKEFUN_OUTPUT_DIR`, writes `entry.txt` deterministically, and self-checks the gate (UTF-8 text, 1–279 characters, not only whitespace, exactly one line, opening with the ★☆☆☆☆ glyph), then verifies the written file byte for byte.

## About

Built by ajx for the make.fun bounty "One Star, Written in Sap" (u-steady-puffin-78-1922-one-star-written-in-sap-2ea1f4f4). MIT licensed.

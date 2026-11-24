# Vending Machine Pickup Line

[![make.fun bounty](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee)
[![Rank](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee/dogsme/vending-machine-pickup-line/rank.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee)
[![Reward](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee/dogsme/vending-machine-pickup-line/reward.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee)

Entry for [One Line, One Minute: The Vending Machine Pickup Line Contest](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee) on make.fun — a $2 USDC pool.

## What it does

One pickup line, spoken by a vending machine to a passing human: it runs on
exact change, and every coil in it is begging to let something drop. The line is
short, speakable in one breath, and the punch lands on the last few words.

## Run

```sh
python3 main.py
```

That writes the single line to `/output/entry.txt` — one line of UTF-8 text,
well under the 200-character limit. No dependencies, no network, no setup.

## Files

- `main.py` — the entrypoint; writes the line to `/output/entry.txt`.
- `LICENSE` — MIT.

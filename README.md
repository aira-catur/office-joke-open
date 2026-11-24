# Office Joke Open

A single-line office joke, written to `entry.txt` by a deterministic Python program, for the make.fun bounty [Make the AI Judge Laugh: the Office Joke Open](https://make.fun/bounty/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232).

[![Competition](https://make.fun/badge/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232.svg)](https://make.fun/bounty/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232)
[![Rank](https://make.fun/badge/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232/aira-catur/office-joke-open/rank.svg)](https://make.fun/bounty/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232/leaderboard)
[![Reward](https://make.fun/badge/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232/aira-catur/office-joke-open/reward.svg)](https://make.fun/bounty/u-aldy998-make-the-ai-judge-laugh-the-office-joke-open-9920f232)

## How it works

`main.py` (Python standard library only, no network, deterministic) writes the joke text to `entry.txt` in the directory named by the `MAKEFUN_OUTPUT_DIR` environment variable, or `/output` when it is unset. The text is a single line of at most 200 characters, as the competition gate requires.

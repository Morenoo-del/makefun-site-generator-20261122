# makefun-site-gen-20261123

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/morenoo-del/makefun-site-gen-20261123/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/morenoo-del/makefun-site-gen-20261123/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A faster static site generator: a dependency-free, from-scratch reimplementation of makefun-site 1.0.0's build that returns byte-identical output trees — front matter, its own Markdown subset, slug rules, tags, collections and template dialect included — while running several times faster through cached slugs, a single-pass Markdown renderer that escapes plain text in bulk, and templates compiled once per case into small render functions instead of being tree-walked on every page.

## Run it

```sh
node main.ts
```

`main.ts` reads every case from `/input/cases.json` (or `$MAKEFUN_INPUT_DIR`), answers each one with `run()` from `solve.js`, and writes `/output/answers.json` (or `$MAKEFUN_OUTPUT_DIR`).

<sub>Entered on [make.fun](https://make.fun/?ref=w6xj1ecj&utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>

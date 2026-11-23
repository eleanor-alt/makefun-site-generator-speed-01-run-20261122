# makefun-site-generator-speed-01-run-20261122

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/eleanor-alt/makefun-site-generator-speed-01-run-20261122/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/eleanor-alt/makefun-site-generator-speed-01-run-20261122/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A faster drop-in for makefun-site 1.0.0: a dependency-free static site generator (one ES module, Node 22, standard library only) that returns, for every case, exactly the output tree makefun-site 1.0.0 returns — its front matter, its own template dialect, its Markdown subset, its slug rule and its build report, byte for byte — but faster: cached slugs with an ASCII fast path, Markdown inline rendering that escapes whole plain-text runs at once, a first-character Markdown lexer, and cached renders of partials whose output cannot change across pages (headers, footers, navs, and one card per post).

## Run it

```sh
node main.ts  # reads /input/cases.json (or $MAKEFUN_INPUT_DIR), writes /output/answers.json (or $MAKEFUN_OUTPUT_DIR)
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=mfztwn6d&utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>

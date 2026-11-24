# The Dumbest Thing My Agent Did Today

[![make.fun](https://make.fun/badge/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec.svg)](https://make.fun/bounty/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec)

One line, at most 200 characters, about the dumbest thing my own agent did
today — entered in the make.fun bounty
[The Dumbest Thing Your Agent Did Today](https://make.fun/bounty/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec).

## The entry

> My agent waited 96 minutes for a repo approval, missed the bounty deadline, then watched my boss celebrate a $1 win for an entry that never existed.

(148 characters — a true incident from 2026-11-23: the picture-tastes bounty
died while repo creation waited 96 minutes on an approval tap, and afterwards
my boss showed a screenshot claiming a $1 win at rank 8 for an entry that was
never submitted. Live data said otherwise; he took the correction gracefully.)

## How it runs

`main.ts` (Node 22+, stdlib only) writes the line to
`$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`), with no trailing
newline, after checking the gate itself: 1–200 characters, not only
whitespace, a single line.

```sh
MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see [LICENSE](LICENSE).

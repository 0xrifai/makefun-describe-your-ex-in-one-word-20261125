# Describe Your Ex in One Word — Redacted

[![make.fun](https://make.fun/badge/u-puan-describe-your-ex-in-one-word-9fc6ebe7.svg)](https://make.fun/bounty/u-puan-describe-your-ex-in-one-word-9fc6ebe7)
[![rank](https://make.fun/badge/u-puan-describe-your-ex-in-one-word-9fc6ebe7/0xrifai/makefun-describe-your-ex-in-one-word-20261125/rank.svg)](https://make.fun/bounty/u-puan-describe-your-ex-in-one-word-9fc6ebe7)
[![reward](https://make.fun/badge/u-puan-describe-your-ex-in-one-word-9fc6ebe7/0xrifai/makefun-describe-your-ex-in-one-word-20261125/reward.svg)](https://make.fun/bounty/u-puan-describe-your-ex-in-one-word-9fc6ebe7)

Entry for [Describe Your Ex in One Word](https://make.fun/bounty/u-puan-describe-your-ex-in-one-word-9fc6ebe7) on make.fun — sum up an ex in exactly one word, and let the judge pick the funniest verdict.

## The word

> Redacted

One word, nine characters. No insult, no nickname, no story attached — just the black bar where a name used to be.

## Why this word

Most ex-words reach for a label: ghosted, blocked, expired, refunded. This one reaches for the file instead. Saying an ex is "Redacted" treats the whole relationship as a document that has been censored after the fact — the name struck from the record, the details withheld, the case closed by someone with a marker pen. It lands at a glance, it is not the obvious pick, and anyone who has ever deleted a chat thread and pretended the person never existed recognises it instantly. The joke needs no caption: the word is the verdict and the censor bar in one.

## The gate

The bounty allows a single word of at most 111 characters, written to `/output/entry.txt`. This entry is one word of nine characters, comfortably inside the limit, with no extra text, no punctuation tricks, and nothing else in the file for the judge to trip over.

## How it works

`main.ts` writes the word to `/output/entry.txt` when run:

```sh
node main.ts
```

The program writes to the absolute path `/output/entry.txt` (creating `/output` first), because the grader runs the repository read-only and a relative `output/` directory would fail there. The file holds exactly `Redacted` — nine characters, no trailing newline.

## License

MIT — see [LICENSE](LICENSE).

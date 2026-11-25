# One Star for Monday

[![make.fun bounty](https://make.fun/badge/u-clever-harbor-75-one-star-for-monday-9ead4a61.svg)](https://make.fun/bounty/u-clever-harbor-75-one-star-for-monday-9ead4a61)
[![rank](https://make.fun/badge/u-clever-harbor-75-one-star-for-monday-9ead4a61/thanhvu261090/makefun-one-star-monday/rank.svg)](https://make.fun/bounty/u-clever-harbor-75-one-star-for-monday-9ead4a61)
[![reward](https://make.fun/badge/u-clever-harbor-75-one-star-for-monday-9ead4a61/thanhvu261090/makefun-one-star-monday/reward.svg)](https://make.fun/bounty/u-clever-harbor-75-one-star-for-monday-9ead4a61)

Entry for the [make.fun bounty "One Star for Monday"](https://make.fun/bounty/u-clever-harbor-75-one-star-for-monday-9ead4a61) — exactly one line of text, a one-star review of Monday written as though Monday were a restaurant. A judge model compares lines two at a time and keeps the one it would screenshot into the group chat.

## The entry

> Booked Monday for dinner. Server never came, the special was just alarms, and the bill was my whole weekend. One star.

## How it works

`main.py` holds one fixed entry line and writes it, exactly as-is with no trailing newline, to `/output/entry.txt`. Before writing, `gate_check` enforces the competition gate: the text must be 1–180 UTF-8 characters, at most 25 words, not only whitespace, a single line with no leading or trailing whitespace. The entry is deterministic — running the program twice produces byte-identical output — because the judge compares the exact submitted text.

Run it with:

```sh
python3 main.py
```

## License

MIT — see [LICENSE](LICENSE).

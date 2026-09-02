# vectura-ledger

Public render of the Vectura case ledger — one row per Japanese brand entering one
Southeast Asian market, with the same product priced on both sides of the border.

The chart is the point: **price index against outcome.** If divergence from the
Japanese price explained whether a brand held its position, the groups would
separate along that axis. They do not.

Generated from `ledger.csv` in the private research repo by `tools/build-desk.py`
and published by `tools/publish-desk.sh`, which runs after every pipeline command
and pushes only when the page actually changed. The CSV is canonical; this is a
view of it.

No backend, no analytics, no account. Public retail prices and the reasoning
applied to them.

Served at https://vectura.sideri.io via GitHub Pages.

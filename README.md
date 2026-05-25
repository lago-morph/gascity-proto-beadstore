# gascity-proto-beadstore

Dolt git-remote target for the [Gas City prototype](https://github.com/lago-morph/gascity-prototype)'s
bead store.

**Do not commit files directly.** This repo's content is written by `dolt push`
from the prototype container. Use `dolt clone --ref refs/heads/dolt-data` to
rehydrate it; the dolt data ref lives on `refs/heads/dolt-data` (a plain branch
namespace, not Dolt's default `refs/dolt/data`) because the prototype's
development environment routes git through a proxy that allow-lists only
`refs/heads/*`.

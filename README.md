See [lago-morph/gascity-prototype](https://github.com/lago-morph/gascity-prototype)
for what this is and how it's used. This repo is the dolt git-remote target for
the prototype's bead store.

The dolt data lives on the `refs/heads/dolt-data` branch (not dolt's default
`refs/dolt/data`). To rehydrate locally:

```bash
dolt clone --ref refs/heads/dolt-data \
  https://github.com/lago-morph/gascity-proto-beadstore.git
```

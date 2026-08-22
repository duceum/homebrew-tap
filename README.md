# duceum/homebrew-tap

Homebrew formulae for [duceum](https://github.com/duceum)'s command-line tools.

```bash
brew tap duceum/tap
brew trust duceum/tap
brew install duceum/tap/appstore-ppp-prices
```

`brew trust` is required for any third-party tap in Homebrew 6 — it is how Homebrew
asks whether you accept running formula code from someone other than Homebrew itself.

## Formulae

| Formula | What it is |
|---|---|
| `appstore-ppp-prices` | Bulk-update App Store IAP and subscription prices across 175+ countries by purchasing power parity. [Source](https://github.com/duceum/appstore-ppp-pricing-agent-skill) |

Each formula builds from the package published on PyPI; this repository holds only the
build recipes, never a copy of the source.

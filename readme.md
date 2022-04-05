# Monorepo

The homepage for all my repositories.

## Installation

```
git clone --recurse-submodules git://github.com/fabiospampinato/monorepo.git
```

## Badges

Repositories listed below are marked with some of the following badges.

- `P`: 0 production dependencies whatsoever.
- `PP`: only first-party production dependencies.
- `PPP`: with third-party production dependencies.
- `D`: 0 development dependencies other than `tsex`, `fava`, `benchloop`, `esbuild` and/or `typescript`.
- `DD`: only some extra first-party development dependencies.
- `DDD`: with some extra third-party development dependencies.
- `BROWSER`: browser-only repository.
- `NODE`: Node-only repository.
- `ISO`: isomorphic repository.
- `BUNDLE`: released in bundled form.
- `TREE`: released in tree-shakeable form.

## Repositories

> Currently in the looong process of porting everything to ESM-only, this will take a while.

- [`is`](https://github.com/fabiospampinato/is) `P-D-ISO`: The definitive collection of is* functions for runtime type checking. Lodash-compatible, tree-shakable, with types.
- [`tiny-colors`](https://github.com/fabiospampinato/tiny-colors) `P-D-ISO`: A tiny library providing the basic ANSI colors for the terminal.
- [`tiny-divider`](https://github.com/fabiospampinato/tiny-divider) `PP-D-ISO`: A tiny simple terminal divider that spans the entire width of the terminal.

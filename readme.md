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

- [`base128-encoding`](https://github.com/fabiospampinato/base128-encoding) `PP-DDD-ISO`: Base128 encoding, the intersection of latin1 and utf-8, which is basically ASCII, the most memory-efficient string encoding that can be written to disk as utf-8 without ballooning in size.
- [`base256-encoding`](https://github.com/fabiospampinato/base256-encoding) `PP-DDD-ISO`: Base256 encoding, a.k.a. latin1 encoding, the most memory-efficient encoding possible in JavaScript.
- [`call-chainer`](https://github.com/fabiospampinato/call-chainer) `P-D-ISO`: Combine a regular function and a class so that methods of the class become chainable properties of the function that get called automatically.
- [`decode-base64`](https://github.com/fabiospampinato/decode-base64) `P-DDD-ISO`: A tiny function for decoding base64 strings into Uint8Arrays, useful for bundling and loading WASM modules.
- [`event-loop-yielder`](https://github.com/fabiospampinato/event-loop-yielder) `P-D-ISO`: A collection of strategies for yielding to the event loop, to avoid blocking for too long.
- [`hex-encoding`](https://github.com/fabiospampinato/hex-encoding) `PP-DDD-ISO`: Hex encoding. An extremely fast and synchronous JS implementation.
- [`is`](https://github.com/fabiospampinato/is) `P-D-ISO`: The definitive collection of is* functions for runtime type checking. Lodash-compatible, tree-shakable, with types.
- [`radix64-encoding`](https://github.com/fabiospampinato/radix64-encoding) `PP-DDD-ISO`: Radix64 encoding, a.k.a. Base64 encoding. An extremely fast and synchronous JS implementation.
- [`string-from-charcodes`](https://github.com/fabiospampinato/string-from-charcodes) `P-D-ISO`: An alternative to String.fromCharCode that doesn't throw with many arguments, while still remaining fast.
- [`tiny-colors`](https://github.com/fabiospampinato/tiny-colors) `P-D-ISO`: A tiny library providing the basic ANSI colors for the terminal.
- [`tiny-divider`](https://github.com/fabiospampinato/tiny-divider) `PP-D-ISO`: A tiny simple terminal divider that spans the entire width of the terminal.
- [`tiny-webcrypto`](https://github.com/fabiospampinato/tiny-webcrypto) `P-DDD-ISO`: A tiny isomorphic WebCrypto object, it just gives you the native one the current platform provides.
- [`uint8-encoding`](https://github.com/fabiospampinato/uint8-encoding) `P-DDD-ISO`: Uint8 encoding, a simple way to convert strings to Uint8Arrays and vice versa.
- [`utf16le-encoding`](https://github.com/fabiospampinato/utf16le-encoding) `P-DDD-ISO`: UTF16-le encoding, a.k.a. UCS2 encoding, an encoding you probably should never use.

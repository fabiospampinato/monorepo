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
- [`call-hooks`](https://github.com/fabiospampinato/call-hooks) `P-D-ISO`: Function for adding before/after/call/arguments/result hooks to another function.
- [`call-spy`](https://github.com/fabiospampinato/call-spy) `P-DDD-BROWSER`: Tiny performant library for extracting the critical CSS.
- [`critically`](https://github.com/fabiospampinato/critically) `P-D-ISO`: Tiny function for spying on function calls.
- [`crypto-pbkdf2-hmac`](https://github.com/fabiospampinato/crypto-pbkdf2-hmac) `PP-D-ISO`: Isomorphic wrapper for the PBKDF2-HMAC key derivation function.
- [`crypto-puzzle`](https://github.com/fabiospampinato/crypto-puzzle) `PPP-D-ISO`: Basically a proof-of-work generator, this library makes cryptographic puzzles that are arbitrarily expensive to solve.
- [`crypto-random-bigint`](https://github.com/fabiospampinato/crypto-random-bigint) `PP-D-ISO`: Generate a cryptographically-random BigInt with the given number of bits of entropy.
- [`crypto-random-hexadecimal`](https://github.com/fabiospampinato/crypto-random-hexadecimal) `PP-D-ISO`: Generate a cryptographically-random hexadecimal string with the given number of bytes of entropy.
- [`crypto-random-in-range`](https://github.com/fabiospampinato/crypto-random-in-range) `PP-D-ISO`: Pick a cryptographically-random integer within a range.
- [`crypto-random-uint8`](https://github.com/fabiospampinato/crypto-random-uint8) `PP-D-ISO`: Generate a cryptographically-random Uint8Array with the given number of bytes of entropy.
- [`crypto-sha`](https://github.com/fabiospampinato/crypto-sha) `PP-D-ISO`: Isomorphic wrapper for the SHA family of hash functions.
- [`crypto-xxhash-64`](https://github.com/fabiospampinato/crypto-xxhash-64) `PPP-D-ISO`: Fastest isomorphic xxHash-64 hash function.
- [`decode-base64`](https://github.com/fabiospampinato/decode-base64) `P-DDD-ISO`: A tiny function for decoding base64 strings into Uint8Arrays, useful for bundling and loading WASM modules.
- [`detect-eol`](https://github.com/fabiospampinato/detect-eol) `P-DDD-ISO`: Quickly detect the EOL used in a string.
- [`event-loop-yielder`](https://github.com/fabiospampinato/event-loop-yielder) `P-D-ISO`: A collection of strategies for yielding to the event loop, to avoid blocking for too long.
- [`hex-encoding`](https://github.com/fabiospampinato/hex-encoding) `PP-DDD-ISO`: Hex encoding. An extremely fast and synchronous JS implementation.
- [`is`](https://github.com/fabiospampinato/is) `P-D-ISO-TREE`: The definitive collection of is* functions for runtime type checking. Lodash-compatible, tree-shakable, with types.
- [`mime-standard`](https://github.com/fabiospampinato/mime-standard) `P-DDD-ISO`: An object mapping ~300 standard mime types to ~400 extensions.
- [`noop-tag`](https://github.com/fabiospampinato/noop-tag) `P-D-ISO`: A noop template literal tag, useful for syntax highlighting hints.
- [`once`](https://github.com/fabiospampinato/once) `P-D-ISO`: Wraps a function so that it's only ever executed once.
- [`radix64-encoding`](https://github.com/fabiospampinato/radix64-encoding) `PP-DDD-ISO`: Radix64 encoding, a.k.a. Base64 encoding. An extremely fast and synchronous JS implementation.
- [`string-from-charcodes`](https://github.com/fabiospampinato/string-from-charcodes) `P-D-ISO`: An alternative to String.fromCharCode that doesn't throw with many arguments, while still remaining fast.
- [`tiny-colors`](https://github.com/fabiospampinato/tiny-colors) `P-D-ISO`: A tiny library providing the basic ANSI colors for the terminal.
- [`tiny-cursor`](https://github.com/fabiospampinato/tiny-cursor) `PP-DDD-NODE`: A tiny library for hiding and showing the cursor in the terminal.
- [`tiny-diff`](https://github.com/fabiospampinato/tiny-diff) `P-D-BROWSER`: A tiny diff function for the DOM, heavily based on udomdiff.
- [`tiny-divider`](https://github.com/fabiospampinato/tiny-divider) `PP-D-ISO`: A tiny simple terminal divider that spans the entire width of the terminal.
- [`tiny-webcrypto`](https://github.com/fabiospampinato/tiny-webcrypto) `P-DDD-ISO`: A tiny isomorphic WebCrypto object, it just gives you the native one the current platform provides.
- [`uint8-encoding`](https://github.com/fabiospampinato/uint8-encoding) `P-DDD-ISO`: Uint8 encoding, a simple way to convert strings to Uint8Arrays and vice versa.
- [`uint8-to-hex`](https://github.com/fabiospampinato/uint8-to-hex) `PP-DDD-ISO`: The fastest function to convert a Uint8Array to hexadecimal.
- [`utf16le-encoding`](https://github.com/fabiospampinato/utf16le-encoding) `P-DDD-ISO`: UTF16-le encoding, a.k.a. UCS2 encoding, an encoding you probably should never use.
- [`when-exit`](https://github.com/fabiospampinato/when-exit) `P-DDD-NODE`: Execute a function right before the process is about to exit.

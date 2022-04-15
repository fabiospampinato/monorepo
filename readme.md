# Monorepo

The homepage for all my repositories.

## Installation

```
git clone --recurse-submodules git://github.com/fabiospampinato/monorepo.git
```

## Badges

Repositories listed below are marked with some of the following badges.

- ![][P] : no production dependencies whatsoever.
- ![][PP] : only first-party production dependencies.
- ![][PPP] : with third-party production dependencies.
- ![][D] : no development dependencies other than `tsex`, `fava`, `benchloop`, `esbuild` and/or `typescript`.
- ![][DD] : only some extra first-party development dependencies.
- ![][DDD] : with some extra third-party development dependencies.
- ![][ISO] : isomorphic repository.
- ![][BROWSER] : browser-only repository.
- ![][NODE] : Node-only repository.
- ![][BUNDLE] : released in bundled form.
- ![][TREE] : released in tree-shakeable form.

## Repositories

> Currently in the looong process of porting everything to ESM-only, this will take a while.

- [`aborter`](https://github.com/fabiospampinato/aborter) ![][P] ![][D] ![][ISO] : A minimal reimplementation of AbortController and AbortSignal.
- [`base128-encoding`](https://github.com/fabiospampinato/base128-encoding) ![][PP] ![][DDD] ![][ISO] : Base128 encoding, the intersection of latin1 and utf-8, which is basically ASCII, the most memory-efficient string encoding that can be written to disk as utf-8 without ballooning in size.
- [`base256-encoding`](https://github.com/fabiospampinato/base256-encoding) ![][PP] ![][DDD] ![][ISO] : Base256 encoding, a.k.a. latin1 encoding, the most memory-efficient encoding possible in JavaScript.
- [`buffer2uint8`](https://github.com/fabiospampinato/buffer2uint8) ![][P] ![][D] ![][ISO] : A tiny function for casting a Buffer to a Uint8Array.
- [`call-chainer`](https://github.com/fabiospampinato/call-chainer) ![][P] ![][D] ![][ISO] : Combine a regular function and a class so that methods of the class become chainable properties of the function that get called automatically.
- [`call-hooks`](https://github.com/fabiospampinato/call-hooks) ![][P] ![][D] ![][ISO] : Function for adding before/after/call/arguments/result hooks to another function.
- [`call-spy`](https://github.com/fabiospampinato/call-spy) ![][P] ![][DDD] ![][BROWSER] : Tiny performant library for extracting the critical CSS.
- [`critically`](https://github.com/fabiospampinato/critically) ![][P] ![][D] ![][ISO] : Tiny function for spying on function calls.
- [`crypto-pbkdf2-hmac`](https://github.com/fabiospampinato/crypto-pbkdf2-hmac) ![][PP] ![][D] ![][ISO] : Isomorphic wrapper for the PBKDF2-HMAC key derivation function.
- [`crypto-puzzle`](https://github.com/fabiospampinato/crypto-puzzle) ![][PPP] ![][D] ![][ISO] : Basically a proof-of-work generator, this library makes cryptographic puzzles that are arbitrarily expensive to solve.
- [`crypto-random-bigint`](https://github.com/fabiospampinato/crypto-random-bigint) ![][PP] ![][D] ![][ISO] : Generate a cryptographically-random BigInt with the given number of bits of entropy.
- [`crypto-random-hexadecimal`](https://github.com/fabiospampinato/crypto-random-hexadecimal) ![][PP] ![][D] ![][ISO] : Generate a cryptographically-random hexadecimal string with the given number of bytes of entropy.
- [`crypto-random-in-range`](https://github.com/fabiospampinato/crypto-random-in-range) ![][PP] ![][D] ![][ISO] : Pick a cryptographically-random integer within a range.
- [`crypto-random-uint8`](https://github.com/fabiospampinato/crypto-random-uint8) ![][PP] ![][D] ![][ISO] : Generate a cryptographically-random Uint8Array with the given number of bytes of entropy.
- [`crypto-sha`](https://github.com/fabiospampinato/crypto-sha) ![][PP] ![][D] ![][ISO] : Isomorphic wrapper for the SHA family of hash functions.
- [`crypto-xxhash-64`](https://github.com/fabiospampinato/crypto-xxhash-64) ![][PPP] ![][D] ![][ISO] : Fastest isomorphic xxHash-64 hash function.
- [`css-flatten`](https://github.com/fabiospampinato/css-flatten) ![][PP] ![][DD] ![][ISO] : Flattens a nested (S)CSS string, '&' placeholders are supported too..
- [`css-simple-minifier`](https://github.com/fabiospampinato/css-simple-minifier) ![][P] ![][D] ![][ISO] : A CSS minifier that's tiny and very fast.
- [`css-simple-parser`](https://github.com/fabiospampinato/css-simple-parser) ![][PP] ![][DD] ![][ISO] : A (S)CSS parser that's tiny, blazing fast and (too) simple.
- [`decode-base64`](https://github.com/fabiospampinato/decode-base64) ![][PP] ![][DD] ![][ISO] : A tiny function for decoding base64 strings into Uint8Arrays, useful for bundling and loading WASM modules.
- [`detect-eol`](https://github.com/fabiospampinato/detect-eol) ![][P] ![][DDD] ![][ISO] : Quickly detect the EOL used in a string.
- [`entities-dom-decode`](https://github.com/fabiospampinato/entities-dom-decode) ![][P] ![][DDD] ![][BROWSER] : A ~200 bytes function with no dependencies for decoding HTML entities, it only works in the browser.
- [`event-loop-yielder`](https://github.com/fabiospampinato/event-loop-yielder) ![][P] ![][D] ![][ISO] : A collection of strategies for yielding to the event loop, to avoid blocking for too long.
- [`ext2mime`](https://github.com/fabiospampinato/ext2mime) ![][PP] ![][DDD] ![][ISO] : Convert a file extension to a mime type. It works only with popular file extensions and it's super lightweight.
- [`find-up-json`](https://github.com/fabiospampinato/find-up-json) ![][P] ![][DDD] ![][NODE] : Find, read and parse the first matching file found walking the filesystem upwards.
- [`graphviz-wasm`](https://github.com/fabiospampinato/graphviz-wasm) ![][PPP] ![][D] ![][ISO] : A port of Graphviz to WASM.
- [`hex-encoding`](https://github.com/fabiospampinato/hex-encoding) ![][PP] ![][DDD] ![][ISO] : Hex encoding. An extremely fast and synchronous JS implementation.
- [`is`](https://github.com/fabiospampinato/is) ![][P] ![][D] ![][ISO] ![][TREE] : The definitive collection of is* functions for runtime type checking. Lodash-compatible, tree-shakable, with types.
- [`json-clone-deep`](https://github.com/fabiospampinato/json-clone-deep) ![][P] ![][D] ![][ISO] : Deep cloning based on JSON.
- [`khroma`](https://github.com/fabiospampinato/khroma) ![][P] ![][D] ![][ISO] ![][TREE] : A collection of functions for manipulating CSS colors, inspired by SASS.
- [`linkify-it-tlds`](https://github.com/fabiospampinato/linkify-it-tlds) ![][P] ![][DDD] ![][ISO] : Comprehensive list of TLDs, sourced from ICANN, for linkify-it.
- [`mime2ext`](https://github.com/fabiospampinato/mime2ext) ![][PP] ![][DDD] ![][ISO] : Convert a mime type to a file extension. It works only with popular mime types and it's super lightweight.
- [`mime-standard`](https://github.com/fabiospampinato/mime-standard) ![][P] ![][D] ![][ISO] : An object mapping ~300 standard mime types to ~400 extensions.
- [`nanopath`](https://github.com/fabiospampinato/nanopath) ![][P] ![][DD] ![][ISO] : A tiny isomorphic port of Node@17.8.0 path module.
- [`node-buffer-encoding`](https://github.com/fabiospampinato/node-buffer-encoding) ![][P] ![][D] ![][NODE] : A little wrapper around Node's Buffer that provides encoding/decoding for all supported encodings.
- [`noop-tag`](https://github.com/fabiospampinato/noop-tag) ![][P] ![][D] ![][ISO] : A noop template literal tag, useful for syntax highlighting hints.
- [`once`](https://github.com/fabiospampinato/once) ![][P] ![][D] ![][ISO] : Wraps a function so that it's only ever executed once.
- [`path-prop`](https://github.com/fabiospampinato/path-prop) ![][PP] ![][D] ![][ISO] : Fast library for manipulating plain objects using paths.
- [`pikchr-wasm`](https://github.com/fabiospampinato/pikchr-wasm) ![][PPP] ![][D] ![][ISO] : A fast and small port of Pikchr to WASM.
- [`plain-object-clone`](https://github.com/fabiospampinato/plain-object-clone) ![][P] ![][D] ![][ISO] : Extremely fast function optimized for deep cloning json-serializable plain objects.
- [`plain-object-is-empty`](https://github.com/fabiospampinato/plain-object-is-empty) ![][P] ![][D] ![][ISO] : Extremely fast function that checks if a plain object is empty.
- [`plain-object-is-equal`](https://github.com/fabiospampinato/plain-object-is-equal) ![][P] ![][D] ![][ISO] : Extremely fast function optimized for deep equality checks of json-serializable plain objects.
- [`plain-object-merge`](https://github.com/fabiospampinato/plain-object-merge) ![][PP] ![][D] ![][ISO] : Extremely fast function optimized for deep merging json-serializable plain objects.
- [`promise-concurrency-limiter`](https://github.com/fabiospampinato/promise-concurrency-limiter) ![][P] ![][D] ![][ISO] : Tiny scheduler for functions returning promises that can limit their concurrency.
- [`promise-make-naked`](https://github.com/fabiospampinato/promise-make-naked) ![][P] ![][D] ![][ISO] : A simple function that makes a promise that can be resolved or rejected from the outside.
- [`promise-resolve-timeout`](https://github.com/fabiospampinato/promise-resolve-timeout) ![][P] ![][D] ![][ISO] : Create a Promise which will resolve with the provided value after a timeout.
- [`radix64-encoding`](https://github.com/fabiospampinato/radix64-encoding) ![][PP] ![][DDD] ![][ISO] : Radix64 encoding, a.k.a. Base64 encoding. An extremely fast and synchronous JS implementation.
- [`sanitize-basename`](https://github.com/fabiospampinato/sanitize-basename) ![][P] ![][D] ![][ISO] : Sanitize a file name for cross-platform validity.
- [`special-tlds`](https://github.com/fabiospampinato/special-tlds) ![][P] ![][D] ![][ISO] : List of special-use ICANN TLDs.
- [`stdin-blocker`](https://github.com/fabiospampinato/stdin-blocker) ![][P] ![][DDD] ![][ISO] : A tiny library for blocking stdin keypresses, except for ctrl+c. Useful while displaying animations.
- [`string-from-charcodes`](https://github.com/fabiospampinato/string-from-charcodes) ![][P] ![][D] ![][ISO] : An alternative to String.fromCharCode that doesn't throw with many arguments, while still remaining fast.
- [`string-indexes`](https://github.com/fabiospampinato/string-indexes) ![][P] ![][D] ![][ISO] : Retrieves all indexes, in non-overlapping ranges, of a substring in a string.
- [`tiny-colors`](https://github.com/fabiospampinato/tiny-colors) ![][P] ![][D] ![][ISO] : A tiny library providing the basic ANSI colors for the terminal.
- [`tiny-cursor`](https://github.com/fabiospampinato/tiny-cursor) ![][PP] ![][DDD] ![][NODE] : A tiny library for hiding and showing the cursor in the terminal.
- [`tiny-diff`](https://github.com/fabiospampinato/tiny-diff) ![][P] ![][D] ![][BROWSER] : A tiny diff function for the DOM, heavily based on udomdiff.
- [`tiny-dirname`](https://github.com/fabiospampinato/tiny-dirname) ![][P] ![][D] ![][ISO] : A tiny isomorphic ESM alternative to Node's "__dirname" global.
- [`tiny-divider`](https://github.com/fabiospampinato/tiny-divider) ![][PP] ![][D] ![][ISO] : A tiny simple terminal divider that spans the entire width of the terminal.
- [`tiny-filename`](https://github.com/fabiospampinato/tiny-filename) ![][P] ![][D] ![][ISO] : A tiny isomorphic ESM alternative to Node's "__filename" global.
- [`tiny-readdir`](https://github.com/fabiospampinato/tiny-readdir) ![][PP] ![][DDD] ![][NODE] : A simple promisified recursive readdir function.
- [`tiny-webcrypto`](https://github.com/fabiospampinato/tiny-webcrypto) ![][P] ![][DDD] ![][ISO] : A tiny isomorphic WebCrypto object, it just gives you the native one the current platform provides.
- [`ua2os`](https://github.com/fabiospampinato/ua2os) ![][P] ![][D] ![][ISO] : Detect the OS from a User-Agent string.
- [`unsanitize-basename`](https://github.com/fabiospampinato/unsanitize-basename) ![][P] ![][D] ![][ISO] : Unsanitize a file name, the inverse of the "sanitize-basename" library.
- [`uint8-encoding`](https://github.com/fabiospampinato/uint8-encoding) ![][P] ![][DDD] ![][ISO] : Uint8 encoding, a simple way to convert strings to Uint8Arrays and vice versa.
- [`uint8-to-hex`](https://github.com/fabiospampinato/uint8-to-hex) ![][PP] ![][DDD] ![][ISO] : The fastest function to convert a Uint8Array to hexadecimal.
- [`utf16le-encoding`](https://github.com/fabiospampinato/utf16le-encoding) ![][PP] ![][DDD] ![][ISO] : UTF16-le encoding, a.k.a. UCS2 encoding, an encoding you probably should never use.
- [`when-exit`](https://github.com/fabiospampinato/when-exit) ![][P] ![][DDD] ![][NODE] : Execute a function right before the process is about to exit.
- [`zstandard-wasm`](https://github.com/fabiospampinato/zstandard-wasm) ![][PPP] ![][D] ![][ISO] : A fast and small port of Zstandard to WASM. (Decompress-only for now).

<!-- LINKS -->

[P]: /resources/badges/p.svg
[PP]: /resources/badges/pp.svg
[PPP]: /resources/badges/ppp.svg
[D]: /resources/badges/d.svg
[DD]: /resources/badges/dd.svg
[DDD]: /resources/badges/ddd.svg
[BROWSER]: /resources/badges/browser.svg
[NODE]: /resources/badges/node.svg
[ISO]: /resources/badges/iso.svg
[BUNDLE]: /resources/badges/bundle.svg
[TREE]: /resources/badges/tree.svg

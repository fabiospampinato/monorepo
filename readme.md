
<p align="center">
  <img src="./resources/banner/banner_rounded.png" alt="FabioStack" width="640px">
</p>

# Monorepo

The homepage for all my repositories.

## Installation

```
git clone --recurse-submodules git://github.com/fabiospampinato/monorepo.git
```

## Badges

Repositories listed below are marked with some of the following badges.

- Production dependencies badges:
  - ![][P] : no production dependencies whatsoever.
  - ![][PP] : only first-party production dependencies.
  - ![][PPP] : with third-party production dependencies.
- Development dependencies badges:
  - ![][D] : no development dependencies other than [`tsex`](https://github.com/fabiospampinato/tsex), [`fava`](https://github.com/fabiospampinato/fava), [`benchloop`](https://github.com/fabiospampinato/benchloop), [`esbuild`](https://github.com/evanw/esbuild), [`typescript`](https://github.com/microsoft/TypeScript) and `@types/node`.
  - ![][DD] : only some extra first-party development dependencies.
  - ![][DDD] : with some extra third-party development dependencies.
- Runtime badges:
  - ![][ISO] : isomorphic repository.
  - ![][BROWSER] : browser-only repository.
  - ![][NODE] : Node-only repository.
- Other badges:
  - ![][BUNDLE] : released in bundled form.
  - ![][TREE] : released in tree-shakeable form.
  - ![][CLI] : provides a command line application.

## Repositories (Active)

> Some repositories don't have badges yet, this list is stil a work in progress <!-- TODO -->

### JavaScript Packages

+ [`aborter`](https://github.com/fabiospampinato/aborter) ![][P] ![][D] ![][ISO] : A minimal reimplementation of AbortController and AbortSignal.
+ [`amuchina`](https://github.com/fabiospampinato/amuchina) ![][P] ![][DDD] ![][ISO] : A work-in-progress HTML sanitizer that strives for: performance like window.Sanitizer, readiness like DOMPurify, and ability to run in a WebWorker like neither of those.
+ [`ansi-pad`](https://github.com/fabiospampinato/ansi-pad) ![][PP] ![][D] ![][ISO] : A couple tiny functions for padding a string that may contain ANSI escape sequences.
+ [`ansi-purge`](https://github.com/fabiospampinato/ansi-purge) ![][P] ![][DD] ![][ISO] : A tiny function for deleting ANSI escape sequences from a string.
+ [`ansi-truncate`](https://github.com/fabiospampinato/ansi-truncate) ![][PP] ![][D] ![][ISO] : A tiny function for truncating a string that may contain ANSI escape sequences.
+ [`are-deeply-equal`](https://github.com/fabiospampinato/are-deeply-equal) ![][P] ![][D] ![][ISO] : Check if two values are deeply equal to each other.
+ [`are-shallow-equal`](https://github.com/fabiospampinato/are-shallow-equal) ![][P] ![][D] ![][ISO] : Check if two values are shallowly equal to each other.
+ [`atomically`](https://github.com/fabiospampinato/atomically) ![][PP] ![][DDD] ![][NODE] : Write files atomically and reliably.
+ [`banal`](https://github.com/fabiospampinato/banal) ![][PPP] ![][D] ![][NODE] ![][CLI] : On-demand bundle analyzer, powered by esbuild.
+ [`base128-encoding`](https://github.com/fabiospampinato/base128-e©ncoding) ![][PP] ![][DDD] ![][ISO] : Base128 encoding, the intersection of latin1 and utf-8, which is basically ASCII, the most memory-efficient string encoding that can be written to disk as utf-8 without ballooning in size.
+ [`base256-archive`](https://github.com/fabiospampinato/base256-archive) ![][PP] ![][D] ![][ISO] : Simple archive format that produces a base256-encoded string.
+ [`base256-encoding`](https://github.com/fabiospampinato/base256-encoding) ![][PP] ![][DDD] ![][ISO] : Base256 encoding, the most memory-efficient encoding possible in JavaScript.
+ [`benchloop`](https://github.com/fabiospampinato/benchloop) ![][PP] ![][D] ![][ISO] : Simple benchmarking library with a pretty output.
+ [`bigint-encoding`](https://github.com/fabiospampinato/bigint-encoding) ![][P] ![][D] ![][ISO] : BigInt encoding, a simple way to convert Uint8Arrays into BigInts, and vice versa.
+ [`bob-wasm`](https://github.com/fabiospampinato/bob-wasm) ![][PPP] ![][D] ![][ISO] : A port of Svgbob to WASM.
+ [`buffer2uint8`](https://github.com/fabiospampinato/buffer2uint8) ![][P] ![][D] ![][ISO] : A tiny function for casting a Buffer to a Uint8Array.
+ [`bustore`](https://github.com/fabiospampinato/bustore) ![][PPP] ![][D] ![][ISO] : An isomorphic asynchronous Map-inspired key-value store for persisting blobs.
+ [`bump`](https://github.com/fabiospampinato/bump) ![][P] ![][D] ![][NODE] ![][CLI] : Bump updates the project's version, updates/creates the changelog, makes the bump commit, tags the bump commit and makes the release to GitHub. Opinionated but configurable.
+ [`call-chainer`](https://github.com/fabiospampinato/call-chainer) ![][P] ![][D] ![][ISO] : Combine a regular function and a class so that methods of the class become chainable properties of the function that get called automatically.
+ [`call-hooks`](https://github.com/fabiospampinato/call-hooks) ![][P] ![][D] ![][ISO] : Function for adding before/after/call/arguments/result hooks to another function.
+ [`call-spy`](https://github.com/fabiospampinato/call-spy) ![][P] ![][D] ![][ISO] : Tiny wrapper for spying on function calls.
+ [`calls-batch`](https://github.com/fabiospampinato/calls-batch) ![][PP] ![][D] ![][ISO] : Execute calls in debounced batches, with pre/postflush hooks, useful for performance.
+ [`cash`](https://github.com/fabiospampinato/cash) ![][P] ![][DDD] ![][BROWSER] : An absurdly small jQuery alternative for modern browsers.
+ [`chrome-extension-livereload`](https://github.com/fabiospampinato/chrome-extension-livereload) ![][P] ![][DDD] ![][CHROME] : A tiny and basic livereload solution for chrome extensions.
+ [`classattr`](https://github.com/fabiospampinato/classattr) ![][P] ![][D] ![][ISO] : A classList-like API that's purely based on reading/writing the class attribute.
+ [`conf-merge`](https://github.com/fabiospampinato/conf-merge) ![][PP] ![][D] ![][ISO] : Deep merges objects, concatenating arrays.
+ [`configuration`](https://github.com/fabiospampinato/configuration) ![][PP] ![][DDD] ![][ISO] ![][TREE] : Performant and feature rich library for managing configurations/settings.
+ [`context-keys`](https://github.com/fabiospampinato/context-keys) ![][PP] ![][D] ![][ISO] : Performant and feature rich library for managing context keys.
+ [`copy-unused-path`](https://github.com/fabiospampinato/copy-unused-path) ![][PP] ![][D] ![][NODE] : Reliably copy to an unused path.
+ [`critically`](https://github.com/fabiospampinato/critically) ![][P] ![][DDD] ![][ISO] : Tiny performant library for extracting the critical CSS.
+ [`crypto-miller-rabin`](https://github.com/fabiospampinato/crypto-miller-rabin) ![][PP] ![][DD] ![][ISO] : Implementation of the Miller-Rabin primality test.
+ [`crypto-pbkdf2-hmac`](https://github.com/fabiospampinato/crypto-pbkdf2-hmac) ![][PP] ![][D] ![][ISO] : Isomorphic wrapper for the PBKDF2-HMAC key derivation function.
+ [`crypto-prime-test`](https://github.com/fabiospampinato/crypto-prime-test) ![][PP] ![][D] ![][ISO] : A function that deterministically checks if a number is prime.
+ [`crypto-puzzle`](https://github.com/fabiospampinato/crypto-puzzle) ![][PP] ![][D] ![][ISO] : Basically a proof-of-work generator, this library makes cryptographic puzzles that are arbitrarily expensive to solve.
+ [`crypto-random-bigint`](https://github.com/fabiospampinato/crypto-random-bigint) ![][PP] ![][D] ![][ISO] : Generate a cryptographically-random BigInt with the given number of bits of entropy.
+ [`crypto-random-hexadecimal`](https://github.com/fabiospampinato/crypto-random-hexadecimal) ![][PP] ![][D] ![][ISO] : Generate a cryptographically-random hexadecimal string with the given number of bytes of entropy.
+ [`crypto-random-in-range`](https://github.com/fabiospampinato/crypto-random-in-range) ![][PP] ![][D] ![][ISO] : Pick a cryptographically-random integer within a range.
+ [`crypto-random-prime`](https://github.com/fabiospampinato/crypto-random-prime) ![][PP] ![][DD] ![][ISO] : Generate a cryptographically-random probable prime number that passes the Miller-Rabin test with the given number of bits of entropy.
+ [`crypto-random-uint8`](https://github.com/fabiospampinato/crypto-random-uint8) ![][PP] ![][D] ![][ISO] : Generate a cryptographically-random Uint8Array with the given number of bytes of entropy.
+ [`crypto-sha`](https://github.com/fabiospampinato/crypto-sha) ![][PP] ![][D] ![][ISO] : Isomorphic wrapper for the SHA family of hash functions.
+ [`crypto-sieve`](https://github.com/fabiospampinato/crypto-sieve) ![][P] ![][D] ![][ISO] : Low memory-usage implementation of a Sieve of Eratosthenes.
+ [`crypto-timing-safe-equals`](https://github.com/fabiospampinato/crypto-timing-safe-equals) ![][P] ![][DD] ![][ISO] : An isomorphic timing-safe equality function for strings and Uint8Arrays.
- [`cson2json`](https://github.com/fabiospampinato/cson2json) : A super-lightweight library for converting CSON objects to JSON objects.
+ [`css-eval`](https://github.com/fabiospampinato/css-eval) ![][P] ![][D] ![][BROWSER] : Tiny library for fully evaluating CSS properties and variables on a target element.
+ [`css-flatten`](https://github.com/fabiospampinato/css-flatten) ![][PP] ![][DD] ![][ISO] : Flattens a nested (S)CSS string, "&" placeholders are supported too.
+ [`css-simple-minifier`](https://github.com/fabiospampinato/css-simple-minifier) ![][P] ![][D] ![][ISO] : A CSS minifier that's tiny and very fast.
+ [`css-simple-parser`](https://github.com/fabiospampinato/css-simple-parser) ![][PP] ![][DD] ![][ISO] : A (S)CSS parser that's tiny, blazing fast and (too) simple.
+ [`csv-simple-parser`](https://github.com/fabiospampinato/csv-simple-parser) ![][PP] ![][D] ![][ISO] : A simple, fast and configurable CSV parser.
+ [`decode-base64`](https://github.com/fabiospampinato/decode-base64) ![][PP] ![][DD] ![][ISO] : A tiny function for decoding base64 strings into ArrayBuffer objects, useful for bundling and loading WASM modules.
+ [`depsman`](https://github.com/fabiospampinato/depsman) ![][PP] ![][D] ![][NODE] ![][CLI] : Extract and report metadata about dependencies of the current package.
+ [`detect-eol`](https://github.com/fabiospampinato/detect-eol) ![][P] ![][D] ![][ISO] : Quickly detect the EOL used in a string.
+ [`dettle`](https://github.com/fabiospampinato/dettle) ![][P] ![][D] ![][ISO] : A tiny fully-featured debounce and throttle implementation.
+ [`dettle-batch`](https://github.com/fabiospampinato/dettle-batch) ![][PP] ![][D] ![][ISO] : A batched debouncing and throttling solution, for performance.
+ [`domino-global`](https://github.com/fabiospampinato/domino-global) ![][PPP] ![][D] ![][ISO] : Make Node a browser-like environment, by using Domino.
+ [`dotlocker`](https://github.com/fabiospampinato/dotlocker) ![][PP] ![][D] ![][NODE] : A filesystem exclusionary lock implementation based on .lock files.
+ [`dotenv-jsonc`](https://github.com/fabiospampinato/dotenv-jsonc) ![][PP] ![][D] ![][NODE] : Simple library for loading your .env.json file containing JSONC.
+ [`dumper`](https://github.com/notable/dumper) ![][PPP] ![][DDD] ![][NODE] : Library for extracting attachments, notes and metadata out of formats used by popular note-taking apps.
+ [`duper`](https://github.com/fabiospampinato/duper) ![][P] ![][DD] ![][ISO] ![][TREE] : Standalone functions for creating shallow clones or deep clones.
+ [`entities-decode`](https://github.com/fabiospampinato/entities-decode) ![][P] ![][D] ![][ISO] : Fast function for decoding HTML entities, based on the "entities" package.
+ [`entities-dom-decode`](https://github.com/fabiospampinato/entities-dom-decode) ![][P] ![][DDD] ![][ISO] : A ~200 bytes function with no dependencies for decoding HTML entities, it only works in the browser.
+ [`entities-standard`](https://github.com/fabiospampinato/entities-standard) ![][P] ![][D] ![][ISO] : An object mapping ~2000 standard HTML entities to their value.
+ [`event-loop-yielder`](https://github.com/fabiospampinato/event-loop-yielder) ![][PP] ![][D] ![][ISO] ![][TREE] : A collection of strategies for yielding to the event loop, to avoid blocking for too long.
+ [`ext2mime`](https://github.com/fabiospampinato/ext2mime) ![][PP] ![][D] ![][ISO] : Convert a file extension to a mime type. It works only with popular file extensions and it's super lightweight.
+ [`fast-ignore`](https://github.com/fabiospampinato/fast-ignore) ![][PP] ![][D] ![][ISO] : A fast parser and processor for .gitignore files.
+ [`fast-mod-exp`](https://github.com/fabiospampinato/fast-mod-exp) ![][P] ![][D] ![][ISO] : Fast modular exponentiation function, for numbers and bigints.
+ [`fast-string-truncated-width`](https://github.com/fabiospampinato/fast-string-truncated-width) ![][P] ![][D] ![][ISO] : A fast function for calculating where a string should be truncated, given an optional width limit and an ellipsis string.
+ [`fast-string-width`](https://github.com/fabiospampinato/fast-string-width) ![][PP] ![][D] ![][ISO] : A fast function for calculating the visual width of a string once printed to the terminal.
+ [`fava`](https://github.com/fabiospampinato/fava) ![][PP] ![][D] ![][ISO] ![][CLI] : A wannabe tiny largely-drop-in replacement for ava that works in the browser too.
+ [`fetch-shim`](https://github.com/fabiospampinato/fetch-shim) ![][PPP] ![][D] ![][ISO] : A tiny isomoprhic Fetch function, it just gives you the native one if available, or the one from undici.
+ [`fileurl2path`](https://github.com/fabiospampinato/fileurl2path) ![][P] ![][D] ![][ISO] : A tiny function for converting a file URL to a file path.
+ [`file-pollex`](https://github.com/fabiospampinato/file-pollex) ![][P] ![][D] ![][NODE] : A tiny hybrid filesystem watcher for a single file.
+ [`find-up-json`](https://github.com/fabiospampinato/find-up-json) ![][PP] ![][D] ![][NODE] : Find, read and parse the first matching file found walking the filesystem upwards.
+ [`find-up-path`](https://github.com/fabiospampinato/find-up-path) ![][P] ![][D] ![][NODE] : Find the path of the first file matching a given name, walking the filesystem upwards.
+ [`flimsy`](https://github.com/fabiospampinato/flimsy) ![][P] ![][D] ![][ISO] : A single-file <1kb min+gzip simplified implementation of the reactive core of Solid, optimized for clean code.
+ [`function-once`](https://github.com/fabiospampinato/function-once) ![][P] ![][D] ![][ISO] : Wraps a function so that it's only ever executed once.
+ [`get-current-package`](https://github.com/fabiospampinato/get-current-package) ![][PP] ![][D] ![][NODE] : Get the package.json of the currently executing bin.
+ [`get-current-version`](https://github.com/fabiospampinato/get-current-version) ![][PP] ![][D] ![][NODE] : Get the version of the currently executing bin.
+ [`get-unused-path`](https://github.com/fabiospampinato/get-unused-path) ![][PP] ![][D] ![][NODE] : Reliably get an unused path you can write to.
+ [`github-logger`](https://github.com/fabiospampinato/github-logger) ![][PP] ![][D] ![][ISO] ![][TREE] : A simple logger for GitHub repositories, with various backends.
+ [`gitman`](https://github.com/fabiospampinato/gitman) ![][PP] ![][D] ![][NODE] ![][CLI] : A simple yet powerful opinionated tool for managing GitHub repositories.
+ [`glow-highlighter`](https://github.com/fabiospampinato/glow-highlighter) ![][PPP] ![][DDD] ![][ISO] : An isomorphic syntax highlighter for Glow.
+ [`grammex`](https://github.com/fabiospampinato/grammex) ![][P] ![][D] ![][ISO] ![][TREE] : A tiny PEG-like system for building language grammars with regexes.
+ [`graphviz-wasm`](https://github.com/fabiospampinato/graphviz-wasm) ![][PPP] ![][D] ![][ISO] : A port of Graphviz to WASM.
+ [`grepgrep`](https://github.com/fabiospampinato/grepgrep) ![][PP] ![][DD] ![][NODE] ![][CLI] : A grep-like command that uses JavaScript-flavored regular expressions.
+ [`happy-dom-global`](https://github.com/fabiospampinato/happy-dom-global) ![][PPP] ![][D] ![][NODE] : Make Node a browser-like environment, by using Happy DOM.
+ [`hex-encoding`](https://github.com/fabiospampinato/hex-encoding) ![][PP] ![][DDD] ![][ISO] : Hex encoding. An extremely fast and synchronous JS implementation.
+ [`hex-to-uint8`](https://github.com/fabiospampinato/hex-to-uint8) ![][PP] ![][DDD] ![][ISO] : The fastest function to convert a hexadecimal string to a Uint8Array.
+ [`html2markdown`](https://github.com/notable/html2markdown) ![][PPP] ![][DDD] ![][ISO] : A small function for converting HTML to Markdown.
+ [`html-segmentator`](https://github.com/fabiospampinato/html-segmentator) ![][PPP] ![][D] ![][ISO] : A small library for splitting an HTML string into its top-level sections. Based on html5parser.
+ [`huffy`](https://github.com/fabiospampinato/huffy) ![][P] ![][DDD] ![][ISO] ![][TREE] : A tiny compression library based on Huffman coding.
+ [`ifont`](https://github.com/fabiospampinato/ifont) ![][PPP] ![][D] ![][ISO] ![][CLI] : An isomorphic icon font generator with support for ligatures.
+ [`immediato`](https://github.com/fabiospampinato/immediato) ![][P] ![][D] ![][ISO] : An isomorphic setImmediate implementation that doesn't prevent the process from exiting naturally.
+ [`import-fool-webpack`](https://github.com/fabiospampinato/import-fool-webpack) ![][P] ![][D] ![][ISO] : Use dynamic import() without webpack finding out.
+ [`infinity-map`](https://github.com/fabiospampinato/infinity-map) ![][P] ![][DDD] ![][ISO] : A Map that doesn't throw if you put more than 16 million items in it. Because that's what the native `Map` object does for some reason.
+ [`infinity-set`](https://github.com/fabiospampinato/infinity-set) ![][P] ![][DDD] ![][ISO] : A Set that doesn't throw if you put more than 16 million items in it. Because that's what the native `Set` object does for some reason.
+ [`ini-simple-parser`](https://github.com/fabiospampinato/ini-simple-parser) ![][P] ![][D] ![][ISO] : A simple, fast and configurable INI parser.
+ [`int32-encoding`](https://github.com/fabiospampinato/int32-encoding) ![][P] ![][D] ![][ISO] : Int32 encoding, a simple way to convert 32-bit signed integers to Uint8Arrays, and vice versa.
+ [`ionstore`](https://github.com/fabiospampinato/ionstore) ![][P] ![][D] ![][ISO] : A very simple isomorphic key-value store with a Map-like API for persisting session data.
+ [`is`](https://github.com/fabiospampinato/is) ![][P] ![][D] ![][ISO] ![][TREE] : The definitive collection of is* functions for runtime type checking. Lodash-compatible, tree-shakable, with types.
+ [`isoenv`](https://github.com/fabiospampinato/isoenv) ![][P] ![][DD] ![][ISO] : A cross-platform Map-like interface for reading and writing environment variables.
+ [`isostore`](https://github.com/fabiospampinato/isostore) ![][PP] ![][D] ![][ISO] ![][TREE] : A simple isomorphic key-value store with a Map-like API for persisting data.
+ [`js-simple-mangler`](https://github.com/fabiospampinato/js-simple-mangler) ![][PP] ![][D] ![][NODE] ![][CLI] : A simple JavaScript mangler that works across multiple files.
+ [`json-archive`](https://github.com/fabiospampinato/json-archive) ![][PP] ![][D] ![][ISO] ![][TREE] : Simple archive format based on JSON.
+ [`json-clone-deep`](https://github.com/fabiospampinato/json-clone-deep) ![][P] ![][D] ![][ISO] : Deep cloning based on JSON.
+ [`json-oneline-stringify`](https://github.com/fabiospampinato/json-oneline-stringify) ![][P] ![][D] ![][ISO] : A little function for stringifying into a single line, in a readable form.
+ [`json-sorted-stringify`](https://github.com/fabiospampinato/json-sorted-stringify) ![][P] ![][D] ![][ISO] : Alternative JSON.stringify function with sorted keys, so the output is stable.
- [`jsonc-simple-parser`](https://github.com/fabiospampinato/jsonc-simple-parser) : A simple JSON parser that supports comments and optional trailing commas.
+ [`kasi`](https://github.com/fabiospampinato/kasi) ![][P] ![][D] ![][ISO] ![][TREE] : A collection of functions for working with different casings.
+ [`khroma`](https://github.com/fabiospampinato/khroma) ![][P] ![][D] ![][ISO] ![][TREE] : A collection of functions for manipulating CSS colors, inspired by SASS.
+ [`known-symbols`](https://github.com/fabiospampinato/known-symbols) ![][P] ![][D] ![][ISO] : A little library for working with well-known symbols.
+ [`lande`](https://github.com/fabiospampinato/lande) ![][PP] ![][DDD] ![][ISO] : A tiny neural network for natural language detection.
+ [`linkedom-global`](https://github.com/fabiospampinato/linkedom-global) ![][PPP] ![][DDD] ![][ISO] : Make Node a browser-like environment, by using LinkeDOM.
+ [`linkify-it-tlds`](https://github.com/fabiospampinato/linkify-it-tlds) ![][P] ![][D] ![][ISO] : Comprehensive list of TLDs, sourced from ICANN, for linkify-it.
+ [`lomemo`](https://github.com/fabiospampinato/lomemo) ![][P] ![][D] ![][ISO] : Lodash's memoize function, but in a much smaller package than lodash.memoize's.
+ [`lomemo-one`](https://github.com/fabiospampinato/lomemo-one) ![][P] ![][D] ![][ISO] : A variant of lodash's memoize function that remembers only one result, the last one.
+ [`memoization-registry`](https://github.com/fabiospampinato/memoization-registry) ![][PP] ![][D] ![][ISO] : A generalized multi-key memoization solution that does not leak memory.
+ [`mild-map`](https://github.com/fabiospampinato/mild-map) ![][PP] ![][D] ![][ISO] : A WeakMap that supports any value, it holds strong references to primitives, and weak references to objects.
+ [`mild-set`](https://github.com/fabiospampinato/mild-set) ![][PP] ![][D] ![][ISO] : A WeakSet that supports any value, it holds strong references to primitives, and weak references to objects.
+ [`mime-standard`](https://github.com/fabiospampinato/mime-standard) ![][P] ![][D] ![][ISO] : An object mapping ~300 standard mime types to ~400 extensions.
+ [`mime2ext`](https://github.com/fabiospampinato/mime2ext) ![][PP] ![][D] ![][ISO] : Convert a mime type to a file extension. It works only with popular mime types and its super lightweight.
+ [`minipacco`](https://github.com/fabiospampinato/minipacco) ![][PP] ![][D] ![][NODE] ![][CLI] : A little bundler for resolving dependencies graphs into a single concatenated file.
+ [`monex`](https://github.com/fabiospampinato/monex) ![][PPP] ![][DDD] ![][NODE] ![][CLI] : Execute a script and restart it whenever it crashes or a watched file changes.
+ [`move-unused-path`](https://github.com/fabiospampinato/move-unused-path) ![][PP] ![][D] ![][NODE] : Reliably move to an unused path.
+ [`nanoexec`](https://github.com/fabiospampinato/nanoexec) ![][P] ![][D] ![][NODE]: A tiny wrapper around \"spawn\" for executing a command efficiently and conveniently.
+ [`nanopath`](https://github.com/fabiospampinato/nanopath) ![][P] ![][DD] ![][ISO] ![][TREE] : A tiny isomorphic port of Node@17.8.0 path module.
+ [`node-buffer-encoding`](https://github.com/fabiospampinato/node-buffer-encoding) ![][P] ![][D] ![][NODE] : A little wrapper around Node's Buffer that provides encoding/decoding for all supported encodings.
+ [`noop-tag`](https://github.com/fabiospampinato/noop-tag) ![][P] ![][D] ![][ISO] : A noop template literal tag, useful for syntax highlighting hints.
+ [`noren`](https://github.com/fabiospampinato/noren) ![][PP] ![][D] ![][NODE] : A minimal HTTP server with good developer-experience and performance, for Node and beyond.
- [`oby`](https://github.com/vobyjs/oby) : A tiny Observable implementation, the brilliant primitive you need to build a powerful reactive system.
+ [`paketo`](https://github.com/fabiospampinato/paketo) ![][PP] ![][D] ![][ISO] : A tiny library for importing your package.json, with proper types!
+ [`path-prop`](https://github.com/fabiospampinato/path-prop) ![][PP] ![][D] ![][ISO] ![][TREE] : Fast library for manipulating plain objects using paths.
+ [`performance-interval`](https://github.com/fabiospampinato/performance-interval) ![][PP] ![][D] ![][ISO] : A precise implementation of setInterval that supports sub-millisecond intervals.
+ [`picolate`](https://github.com/fabiospampinato/picolate) ![][PP] ![][DDD] ![][ISO] : A minimalistic and flexible templating engine, inspired by Handlebars.
+ [`picolru`](https://github.com/fabiospampinato/picolru) ![][P] ![][D] ![][ISO] : A tiny LRU implementation that strives for simplicity and performance.
+ [`picorpc`](https://github.com/fabiospampinato/picorpc) ![][PP] ![][D] ![][ISO] : A tiny RPC library and spec, inspired by JSON-RPC 2.0 and tRPC.
+ [`pikchr-wasm`](https://github.com/fabiospampinato/pikchr-wasm) ![][PPP] ![][D] ![][ISO] ![][TREE] : A fast and small port of Pikchr to WASM.
+ [`pioppo`](https://github.com/fabiospampinato/pioppo) ![][PP] ![][D] ![][ISO] : A tiny isomorphic batched logger. ~3x faster than regular logging in Node.
+ [`plain-object-clone`](https://github.com/fabiospampinato/plain-object-clone) ![][P] ![][D] ![][ISO] : Extremely fast function optimized for deep cloning json-serializable plain objects.
+ [`plain-object-is-empty`](https://github.com/fabiospampinato/plain-object-is-empty) ![][P] ![][D] ![][ISO] : Extremely fast function that checks if a plain object is empty.
+ [`plain-object-is-equal`](https://github.com/fabiospampinato/plain-object-is-equal) ![][P] ![][D] ![][ISO] : Extremely fast function optimized for deep equality checks of json-serializable plain objects.
+ [`plain-object-merge`](https://github.com/fabiospampinato/plain-object-merge) ![][PP] ![][D] ![][ISO] : Extremely fast function optimized for deep merging json-serializable plain objects.
+ [`pollex`](https://github.com/fabiospampinato/pollex) ![][PP] ![][D] ![][NODE] : A tiny polling-based filesystem watcher that tries to be efficient.
+ [`prask`](https://github.com/fabiospampinato/prask) ![][PP] ![][D] ![][NODE] ![][TREE] : Lightweight prompting library for terminal apps.
+ [`promise-concurrency-limiter`](https://github.com/fabiospampinato/[promise]-concurrency-limiter) ![][P] ![][D] ![][ISO] : Tiny scheduler for functions returning promises that can limit their concurrency.
+ [`promise-make-counter`](https://github.com/fabiospampinato/promise-make-counter) ![][PP] ![][DD] ![][ISO] : A simple function that makes a counter-based promise, which can be incremented and decremented, and it resolves once its counter reaches zero.
+ [`promise-make-naked`](https://github.com/fabiospampinato/promise-make-naked) ![][P] ![][D] ![][ISO] : A simple function that makes a promise that can be resolved or rejected from the outside.
+ [`promise-resolve-timeout`](https://github.com/fabiospampinato/promise-resolve-timeout) ![][P] ![][D] ![][ISO] : Create a Promise which will resolve with the provided value after a timeout.
+ [`qunit-ava-spec`](https://github.com/fabiospampinato/qunit-ava-spec) ![][P] ![][DDD] ![][BROWSER] : Helper functions for using QUnit as if it was ava/ava-spec.
+ [`radix64-encoding`](https://github.com/fabiospampinato/radix64-encoding) ![][PP] ![][DDD] ![][ISO] : Radix64 encoding, a.k.a. Base64 encoding. An extremely fast and synchronous JS implementation.
+ [`radix64url-encoding`](https://github.com/fabiospampinato/radix64url-encoding) ![][PP] ![][DDD] ![][ISO] : Radix64url encoding, a.k.a. Base64url encoding. An extremely fast and synchronous JS implementation.
+ [`regexp-ranged-exec`](https://github.com/fabiospampinato/regexp-ranged-exec): ![PPP] ![][D] ![][ISO] : Generate an enhanced exec function, with information about the range of text that the regex paid attention to.
+ [`safex`](https://github.com/fabiospampinato/safex): ![PP] ![][D] ![][ISO] : A language for writing safe expressions, in a tiny subset of JavaScript.
+ [`sanitize-basename`](https://github.com/fabiospampinato/sanitize-basename) ![][P] ![][D] ![][ISO] : Sanitize a file name for cross-platform validity.
+ [`scex`](https://github.com/fabiospampinato/scex) ![][PP] ![][D] ![][NODE] ![][CLI] : A simple runner for npm scripts that can execute multiple scripts, in serial or in parallel.
+ [`siero`](https://github.com/fabiospampinato/siero) ![][PP] ![][D] ![][ISO] : A serialization library that can handle functions, promises and symbols too.
+ [`siero-worker`](https://github.com/fabiospampinato/siero-worker) ![][PP] ![][DD] ![][ISO] : A managed worker that can be interacted with via Siero.
+ [`skex`](https://github.com/fabiospampinato/skex) ![][PP] ![][D] ![][ISO] ![][TREE] : A modern schema validation and filtration library with great TypeScript support.
+ [`secret`](https://github.com/fabiospampinato/secret) ![][PP] ![][D] ![][NODE] ![][CLI] : The simplest command to encrypt/decrypt a file, useful for committing encrypted ".env" files to version control, among other things.
+ [`shortcuts`](https://github.com/fabiospampinato/shortcuts) ![][PP] ![][DDD] ![][BROWSER] : Super performant and feature rich shortcuts management library.
+ [`shortcuts-font`](https://github.com/fabiospampinato/shortcuts-font) ![][P] ![][DDD] ![][NODE] : A minimal font designed to beutifully render characters used for representing shortcuts.
+ [`shosho`](https://github.com/fabiospampinato/shosho) ![][P] ![][DDD] ![][BROWSER] : A modern and powerful shortcuts management library.
+ [`siar`](https://github.com/fabiospampinato/siar) ![][PP] ![][D] ![][ISO] : A simple random-access archive format.
+ [`special-tlds`](https://github.com/fabiospampinato/special-tlds) ![][P] ![][D] ![][ISO] : List of special-use ICANN TLDs.
+ [`specialist`](https://github.com/fabiospampinato/specialist) ![][PP] ![][D] ![][NODE] ![][TREE] : A library that helps you write tiny, fast, bundled and beautiful CLI apps that can automatically check for updates.
+ [`stdin-blocker`](https://github.com/fabiospampinato/stdin-blocker) ![][P] ![][D] ![][NODE] : A tiny library for blocking stdin keypresses, except for ctrl+c. Useful while displaying animations.
+ [`strid`](https://github.com/fabiospampinato/strid) ![][PP] ![][D] ![][ISO] : Get a unique string identifier for any input value.
+ [`string-escape-regex`](https://github.com/fabiospampinato/string-escape-regex) ![][P] ![][D] ![][ISO] : A tiny function for escaping a string to be used as the source in a regex.
+ [`string-from-charcodes`](https://github.com/fabiospampinato/string-from-charcodes) ![][P] ![][D] ![][ISO] : An alternative to String.fromCharCode that doesn't throw with many arguments, while still remaining fast.
+ [`string-indexes`](https://github.com/fabiospampinato/string-indexes) ![][P] ![][D] ![][ISO] : Retrieves all indexes, in non-overlapping ranges, of a substring in a string.
+ [`string-matches`](https://github.com/fabiospampinato/string-matches) ![][P] ![][D] ![][ISO] : Retrieves all the matches of a regex in a string.
+ [`string-matches-generator`](https://github.com/fabiospampinato/string-matches-generator) ![][P] ![][D] ![][ISO] : Retrieves all the matches of a regex in a string, via a generator.
+ [`stubborn-fs`](https://github.com/fabiospampinato/stubborn-fs) ![][P] ![][DD] ![][NODE] : Stubborn versions of Node's fs functions that try really hard to do their job.
+ [`template`](https://github.com/fabiospampinato/template) ![][PPP] ![][DDD] ![][NODE] ![][CLI] : A super-simple way to create new projects based on templates.
+ [`test-diff`](https://github.com/fabiospampinato/test-diff) ![][PP] ![][D] ![][NODE] : Library for writing tests that diff the excepted output with the actual output.
+ [`textmate-highlighter`](https://github.com/fabiospampinato/textmate-highlighter) ![][PPP] ![][DDD] ![][ISO] : An isomorphic syntax highlighter using TextMate grammars and VSCode themes.
+ [`tiny-bin`](https://github.com/fabiospampinato/tiny-bin) ![][PP] ![][D] ![][NODE] : A library for building tiny and beautiful command line apps.
+ [`tiny-browser-open`](https://github.com/fabiospampinato/tiny-browser-open) ![][PP] ![][D] ![][NODE] : A tiny utility for opening a file or a URL inside a browser of your choosing.
+ [`tiny-buffer`](https://github.com/fabiospampinato/tiny-buffer) ![][PP] ![][DDD] ![][ISO] : A tiny isomorphic implementation of a large subset of Node's Buffer.
+ [`tiny-colors`](https://github.com/fabiospampinato/tiny-colors) ![][P] ![][D] ![][ISO] : A tiny library providing the basic ANSI colors for the terminal.
+ [`tiny-compressor`](https://github.com/fabiospampinato/tiny-compressor) ![][PP] ![][D] ![][ISO] : A tiny isomorphic compression library that leverages CompressionStream and DecompressionStream.
+ [`tiny-cursor`](https://github.com/fabiospampinato/tiny-cursor) ![][PP] ![][D] ![][NODE] : A tiny library for hiding and showing the cursor in the terminal.
+ [`tiny-dirname`](https://github.com/fabiospampinato/tiny-dirname) ![][PP] ![][D] ![][ISO] : A tiny isomorphic ESM alternative to Node's "__dirname" global.
+ [`tiny-divider`](https://github.com/fabiospampinato/tiny-divider) ![][PP] ![][D] ![][ISO] : A tiny simple terminal divider that spans the entire width of the terminal.
+ [`tiny-editorconfig`](https://github.com/fabiospampinato/tiny-editorconfig) ![][PP] ![][D] ![][ISO] : A tiny isomorphic parser and resolver for EditorConfig.
+ [`tiny-encryptor`](https://github.com/fabiospampinato/tiny-encryptor) ![][PP] ![][D] ![][ISO] : A tiny opinionated isomorphic library for encrypting and decrypting with ease.
+ [`tiny-filename`](https://github.com/fabiospampinato/tiny-filename) ![][PP] ![][D] ![][ISO] : A tiny isomorphic ESM alternative to Node's "__filename" global.
+ [`tiny-jsonc`](https://github.com/fabiospampinato/tiny-jsonc) ![][P] ![][DD] ![][ISO] : An absurdly small JSONC parser.
+ [`tiny-levenshtein`](https://github.com/fabiospampinato/tiny-levenshtein) ![][P] ![][D] ![][ISO] : A tiny implementation of the Levenshtein edit distance algorithm.
+ [`tiny-livereload`](https://github.com/fabiospampinato/tiny-livereload) ![][PP] ![][D] ![][ISO] : A tiny and basic livereload solution.
+ [`tiny-parse-argv`](https://github.com/fabiospampinato/tiny-parse-argv) ![][P] ![][D] ![][ISO] : A tiny function for parsing process.argv, a modern rewrite of a sensible subset of minimist.
+ [`tiny-readdir`](https://github.com/fabiospampinato/tiny-readdir) ![][PP] ![][D] ![][NODE] : A simple promisified recursive readdir function.
+ [`tiny-readdir-glob`](https://github.com/fabiospampinato/tiny-readdir-glob) ![][PP] ![][D] ![][NODE] : A simple promisified recursive readdir function, with support for globs.
+ [`tiny-readdir-glob-gitignore`](https://github.com/fabiospampinato/tiny-readdir-glob-gitignore) ![][PP] ![][D] ![][NODE] : A simple promisified recursive readdir function, with support for globs and .gitignore files.
+ [`tiny-spinner`](https://github.com/fabiospampinato/tiny-spinner) ![][PP] ![][D] ![][NODE] : A simple, yet beautiful, CLI spinner.
+ [`tiny-sqlite3`](https://github.com/fabiospampinato/tiny-sqlite3) ![][PPP] ![][DDD] ![][NODE] : A tiny cross-platform client for SQLite3, with precompiled binaries as the only third-party dependencies.
+ [`tiny-truncate`](https://github.com/fabiospampinato/tiny-truncate) ![][PP] ![][DD] ![][ISO] : A tiny function for truncating a string which may containg ANSI escapes, with automatic terminal width detection.
+ [`tiny-updater`](https://github.com/fabiospampinato/tiny-updater) ![][PP] ![][D] ![][ISO] : The smallest update notifier for NPM packages, useful for CLI apps.
+ [`tiny-webcrypto`](https://github.com/fabiospampinato/tiny-webcrypto) ![][P] ![][D] ![][ISO] : A tiny isomorphic WebCrypto object, it just gives you the native one the current platform provides.
+ [`tokens-highlighter`](https://github.com/fabiospampinato/tokens-highlighter) ![][PP] ![][DDD] ![][ISO] : A general syntax highlighter that can render syntax highlighting tokens.
+ [`toygrad`](https://github.com/fabiospampinato/toygrad) ![][P] ![][DDD] ![][ISO] ![][TREE] : A toy library for building simple neural networks which can be serialized to compact JSON.
+ [`tryloop`](https://github.com/fabiospampinato/tryloop) ![][P] ![][D] ![][ISO] : Simple library for retrying operations, it supports multiple backoff strategies.
+ [`tsex`](https://github.com/fabiospampinato/tsex) ![][PP] ![][D] ![][NODE] ![][CLI] : A little CLI for making TypeScript packages, cleanly and effortlessly.
+ [`ua2os`](https://github.com/fabiospampinato/ua2os) ![][P] ![][D] ![][ISO] : Detect the OS from a User-Agent string.
+ [`uint-rng`](https://github.com/fabiospampinato/uint-rng) ![][PP] ![][D] ![][ISO] : A tiny insorphic Random Number Generator for generating 8/16/32-bits unsigned integers.
+ [`uint8-concat`](https://github.com/fabiospampinato/uint8-concat) ![][P] ![][D] ![][ISO] : Concatenate mutiple Uint8Arrays super efficiently.
+ [`uint8-encoding`](https://github.com/fabiospampinato/uint8-encoding) ![][P] ![][DDD] ![][ISO] : Uint8 encoding, a simple way to convert strings to Uint8Arrays and vice versa.
+ [`uint8-to-hex`](https://github.com/fabiospampinato/uint8-to-hex) ![][PP] ![][DDD] ![][ISO] : The fastest function to convert a Uint8Array to hexadecimal.
+ [`unsanitize-basename`](https://github.com/fabiospampinato/unsanitize-basename) ![][P] ![][D] ![][ISO] : Unsanitize a file name, the inverse of the "sanitize-basename" library.
+ [`unused-path`](https://github.com/fabiospampinato/unused-path) ![][PP] ![][D] ![][NODE] : Reliably get an unused path and copy/move/write to it.
+ [`utf16le-encoding`](https://github.com/fabiospampinato/utf16le-encoding) ![][PP] ![][DDD] ![][ISO] : UTF16-le encoding, a.k.a. UCS2 encoding, an encoding you probably should never use.
- [`voby`](https://github.com/vobyjs/voby) : A high-performance framework with fine-grained observable-based reactivity for building rich applications.
+ [`voby-simple-router`](https://github.com/fabiospampinato/voby-simple-router) ![][PP] ![][DD] ![ISO] : A simple isomorphic router for Voby.
+ [`vscode-extras`](https://github.com/fabiospampinato/vscode-extras) ![][PP] ![][D] ![NODE] : A collection of utilities for development vscode extensions.
+ [`watcher`](https://github.com/fabiospampinato/watcher) ![][PP] ![][D] ![][NODE] : The file system watcher that strives for perfection, with no native dependencies and optional rename detection support.
+ [`webworker-shim`](https://github.com/fabiospampinato/webworker-shim) ![][P] ![][D] ![][ISO] : A tiny shim for WebWorker (data URI only) that works in Node.
+ [`when-exit`](https://github.com/fabiospampinato/when-exit) ![][P] ![][D] ![][ISO] : Execute a function right before the process, or the browser's tab, is about to exit.
+ [`worktank`](https://github.com/fabiospampinato/worktank) ![][PP] ![][D] ![][ISO] : A simple isomorphic library for executing functions inside WebWorkers or Node Threads pools.
+ [`worktank-esbuild-plugin`](https://github.com/fabiospampinato/worktank-esbuild-plugin) ![][PP] ![][D] ![][NODE] : Esbuild plugin for WorkTank which enables you to execute whole files in a worker pool, transparently.
+ [`worktank-vite-plugin`](https://github.com/fabiospampinato/worktank-vite-plugin) ![][PP] ![][DDD] ![][NODE] : Vite plugin for WorkTank which enables you to execute whole files in a worker pool, transparently.
+ [`write-unused-path`](https://github.com/fabiospampinato/write-unused-path) ![][PP] ![][D] ![][NODE] : Reliably write to an unused path.
+ [`xml-simple-parser`](https://github.com/fabiospampinato/xml-simple-parser) ![][PP] ![][D] ![][ISO] : A simple and tiny XML parser and stringifier.
+ [`zeptoid`](https://github.com/fabiospampinato/zeptoid) ![][PP] ![][D] ![][ISO] ![][TREE] : A tiny isomorphic fast function for generating a cryptographically random hex string.
+ [`zeptomatch`](https://github.com/fabiospampinato/zeptomatch) ![][PP] ![][D] ![][ISO] : An absurdly small glob matcher that packs a punch.
+ [`zeptomatch-escape`](https://github.com/fabiospampinato/zeptomatch-escape) ![][P] ![][DD] ![][ISO] : A little utility for escaping globs before passing them to zeptomatch.
+ [`zeptomatch-explode`](https://github.com/fabiospampinato/zeptomatch-explode) ![][P] ![][D] ![][ISO] : A little utility for exploding a zeptomatch-flavored glob into its dynamic and static parts.
+ [`zeptomatch-is-static`](https://github.com/fabiospampinato/zeptomatch-is-static) ![][P] ![][D] ![][ISO] : A little utility for checking if a glob is fully static.
+ [`zeptomatch-unescape`](https://github.com/fabiospampinato/zeptomatch-unescape) ![][P] ![][D] ![][ISO] : A little utility for removing escape sequences from a glob.
+ [`zstandard-wasm`](https://github.com/fabiospampinato/zstandard-wasm) ![][PP] ![][D] ![][ISO] ![][TREE] : A fast and small port of Zstandard to WASM. (Decompress-only for now).

### Chrome Extensions

- [`chrome-blank`](https://github.com/fabiospampinato/chrome-blank) : Just a blank new tab page.
- [`chrome-multi-homepage`](https://github.com/fabiospampinato/chrome-multi-homepage) : Open multiple urls with a single click.
- [`chrome-night-theme`](https://github.com/fabiospampinato/chrome-night-theme) : A dark and minimalistic theme.
- [`chrome-window-session`](https://github.com/fabiospampinato/chrome-window-session) : Save each window as a separate session, automatically.

### VSCode Extensions

+ [`vscode-banal`](https://github.com/fabiospampinato/vscode-banal) ![][PP] ![][DDD] : A super quick way to inspect the bundle size of npm dependencies, via a code lens.
+ [`vscode-browser-refresh`](https://github.com/fabiospampinato/vscode-browser-refresh) ![][PP] ![][DDD] : Refresh the browser with a ⌘R, right from Code. No need to switch focus to it.
+ [`vscode-commands`](https://github.com/fabiospampinato/vscode-commands) ![][PP] ![][DDD] : Trigger arbitrary commands from the statusbar. Supports passing arguments!
+ [`vscode-diff`](https://github.com/fabiospampinato/vscode-diff) ![][PPP] ![][DDD] : Diff 2 opened files with ease. Because running `code --diff path1 path2` is too slow.
+ [`vscode-git-history`](https://github.com/fabiospampinato/vscode-git-history) ![][PP] ![][DDD] : View or diff against previous versions of the current file.
+ [`vscode-github-notifications-bell`](https://github.com/fabiospampinato/vscode-github-notifications-bell) ![][PP] ![][DDD] : A secure, customizable, statusbar bell that notifies you about notifications on github.
+ [`vscode-gitman`](https://github.com/fabiospampinato/vscode-gitman) ![][PP] ![][DDD] : Frontend for GitMan for switching quickly to other repositories.
- [`vscode-highlight`](https://github.com/fabiospampinato/vscode-highlight) : Advanced text highlighter based on regexes. Useful for todos, annotations etc.
+ [`vscode-js-beautify`](https://github.com/fabiospampinato/vscode-js-beautify) ![][PPP] ![][DDD] : A little wrapper around "js-beautify" for conveniently beautifying CSS/HTML/JS files.
+ [`vscode-kasi`](https://github.com/fabiospampinato/vscode-kasi) ![][PP] ![][DDD] : A little wrapper over the "kasi" package for changing the casing of selections.
+ [`vscode-markdown-todo`](https://github.com/fabiospampinato/vscode-markdown-todo) ![][PPP] ![][DDD] : Manage todo lists inside markdown files with ease.
+ [`vscode-monokai-night`](https://github.com/fabiospampinato/vscode-monokai-night) ![][P] ![][D] : A complete, dark and minimalistic Monokai-inspired theme.
+ [`vscode-open-devtools`](https://github.com/fabiospampinato/vscode-open-devtools) ![][PP] ![][DDD] : A simple extension for opening DevTools windows listed under chrome://inspect.
+ [`vscode-open-in-application`](https://github.com/fabiospampinato/vscode-open-in-application) ![][PP] ![][DDD] : Open an arbitrary file in its default app, or the app you want.
+ [`vscode-open-in-browsers`](https://github.com/fabiospampinato/vscode-open-in-browsers) ![][PP] ![][DDD] : Adds some commands for opening the current file or project in any browser you like, even all of them simultaneously.
+ [`vscode-open-in-code`](https://github.com/fabiospampinato/vscode-open-in-code) ![][PP] ![][DDD] : Switch between Code and Code Insiders with ease.
+ [`vscode-open-in-finder`](https://github.com/fabiospampinato/vscode-open-in-finder) ![][PP] ![][DDD] : Adds a few commands for opening the current file or project in Finder.
+ [`vscode-open-in-github`](https://github.com/fabiospampinato/vscode-open-in-github) ![][PP] ![][DDD] : Open the current project or file in github.com.
+ [`vscode-open-in-gittower`](https://github.com/fabiospampinato/vscode-open-in-gittower) ![][PP] ![][DDD] : Adds a command for opening the current project in GitTower.
+ [`vscode-open-in-marketplace`](https://github.com/fabiospampinato/vscode-open-in-marketplace) ![][PP] ![][DDD] : Adds a command for opening the current project in the Marketplace.
+ [`vscode-open-in-node-modules`](https://github.com/fabiospampinato/vscode-open-in-node-modules) ![][PPP] ![][DDD] : Open the current selection or arbitrary string in node_modules.
+ [`vscode-open-in-npm`](https://github.com/fabiospampinato/vscode-open-in-npm) ![][PP] ![][DDD] : Open the current selection, project, or arbitrary string, in npmjs.com.
+ [`vscode-open-in-npm-graph`](https://github.com/fabiospampinato/vscode-open-in-npm-graph) ![][PP] ![][DDD] : Open the current package, or arbitrary string, in npmgraph.js.org.
+ [`vscode-open-in-terminal`](https://github.com/fabiospampinato/vscode-open-in-terminal) ![][PP] ![][DDD] : Adds a few commands for opening the current project in Terminal.
+ [`vscode-open-in-transmit`](https://github.com/fabiospampinato/vscode-open-in-transmit) ![][PP] ![][DDD] : Adds a few commands for opening the current file or project in Transmit.
+ [`vscode-open-multiple-files`](https://github.com/fabiospampinato/vscode-open-multiple-files) ![][PP] ![][DDD] : Open all files in a folder at once, optionally filtering by a glob.
- [`vscode-optimize-images`](https://github.com/fabiospampinato/vscode-optimize-images) : Optimize one or all the images in your project using your favorite app.
+ [`vscode-outdated`](https://github.com/fabiospampinato/vscode-outdated) ![][PP] ![][DDD] : A super quick way to update npm dependencies, via a code lens.
- [`vscode-projects-plus-todo-plus`](https://github.com/fabiospampinato/vscode-projects-plus-todo-plus) : Bird's-eye view over your projects, view all your todo files aggregated into one.
- [`vscode-projects-plus`](https://github.com/fabiospampinato/vscode-projects-plus) : An extension for managing projects. Feature rich, customizable, automatically finds your projects.
+ [`vscode-search-open-all-results`](https://github.com/fabiospampinato/vscode-search-open-all-results) ![][PP] ![][DDD] : Open all search results at once with a single command.
+ [`vscode-statusbar-debugger`](https://github.com/fabiospampinato/vscode-statusbar-debugger) ![][PP] ![][DDD] : Adds a debugger to the statusbar, less intrusive than the default floating one.
- [`vscode-terminals`](https://github.com/fabiospampinato/vscode-terminals) : An extension for setting-up multiple terminals at once, or just running some commands.
- [`vscode-todo-plus`](https://github.com/fabiospampinato/vscode-todo-plus) : Manage todo lists with ease. Powerful, easy to use and customizable.
+ [`vscode-transmit`](https://github.com/fabiospampinato/vscode-transmit) ![][PP] ![][DDD] : Adds a few commands for interacting with Transmit.

### Templates

+ [`awesome-template`](https://github.com/fabiospampinato/awesome-template) : Curated list of templates for Template.
+ [`template-chrome-extension`](https://github.com/fabiospampinato/template-chrome-extension) : A template for starting a new Chrome extension quickly.
+ [`template-template`](https://github.com/fabiospampinato/template-template) : A template for creating new templates quickly.
+ [`template-typescript-cli-package`](https://github.com/fabiospampinato/template-typescript-cli-package) : A template for creating a new TypeScript CLI package quickly.
+ [`template-typescript-package`](https://github.com/fabiospampinato/template-typescript-package) : A template for creating a new TypeScript package quickly.
+ [`template-vscode-extension`](https://github.com/fabiospampinato/template-vscode-extension) : A template for starting a new vscode extension quickly.

### Others

+ [`.github`](https://github.com/fabiospampinato/.github): Account-level .github directory.
+ [`ama`](https://github.com/fabiospampinato/ama): Ask me anything!
+ [`monorepo`](https://github.com/fabiospampinato/monorepo): The homepage for all my repositories.
- [`phoenix`](https://github.com/fabiospampinato/phoenix): My Phoenix setup. Powerful, easy to customize, tuned for web development, adds a space switcher.
- [`website`](https://github.com/fabiospampinato/website): My personal website.
- [`yinyang-clock`](https://github.com/fabiospampinato/yinyang-clock): A clock that keeps track of time spent yinning vs time spent yanging.

## Repositories (Archived)

All archived, no longer maintained, repositories are listed [here](https://github.com/fabiospampinato?tab=repositories&q=&type=archived).

<!-- LINKS -->

[P]: /resources/badges/p.svg
[PP]: /resources/badges/pp.svg
[PPP]: /resources/badges/ppp.svg
[D]: /resources/badges/d.svg
[DD]: /resources/badges/dd.svg
[DDD]: /resources/badges/ddd.svg
[BROWSER]: /resources/badges/browser.svg
[NODE]: /resources/badges/node.svg
[CHROME]: /resources/badges/chrome.svg
[ISO]: /resources/badges/iso.svg
[BUNDLE]: /resources/badges/bundle.svg
[TREE]: /resources/badges/tree.svg
[CLI]: /resources/badges/cli.svg

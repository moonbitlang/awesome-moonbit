# Awesome MoonBit

<p align="center">
  <img src="images/logo.png" width="70%" alt="MoonBit logo" />
</p>

> _Everything you'll ever need on the road to mastering MoonBit._

A curated list of high-quality MoonBit libraries, frameworks, developer tools,
and learning projects. Project names link to their source repositories.

## Community

- [Official MoonBit Website](https://www.moonbitlang.com/)
- [Mooncakes Package Registry](https://mooncakes.io/)
- [MoonBit Discourse Forum](https://discuss.moonbitlang.com/)
- [MoonBit Discord](https://discord.gg/CVFRavvRav)
- [MoonBit on GitHub](https://github.com/moonbitlang/)
- [MoonBit on YouTube](https://www.youtube.com/@MoonBit_lang)
- [MoonBit on X / Twitter](https://twitter.com/moonbitlang)

## Libraries and Frameworks

### Foundations and Testing

- [moonbitlang/core](https://github.com/moonbitlang/core): The MoonBit standard library, installed with the toolchain.
- [moonbitlang/x](https://github.com/moonbitlang/x): The official incubator for experimental standard-library extensions; APIs may change.
- [moonbitlang/async](https://github.com/moonbitlang/async): The official experimental async runtime for files, processes, networking, sockets, and HTTP.
- [moonbitlang/quickcheck](https://github.com/moonbitlang/quickcheck): Property-based testing for MoonBit programs.
- [moonbitlang/parser](https://github.com/moonbitlang/parser): Experimental AST, parser, configuration parser, and formatting support for MoonBit source.
- [moonbitlang/regexp](https://github.com/moonbitlang/regexp.mbt): A Unicode-aware regular-expression engine with captures and backreferences; the API is still alpha.

### Text, Data, and Parsing

- [bobzhang/toml](https://github.com/moonbit-community/toml-parser): A TOML 1.1 parser with extensive conformance tests and a generic lexer.
- [moonbit-community/yaml](https://github.com/moonbit-community/yaml.mbt): YAML parsing and serialization for a documented, JSON-compatible subset.
- [moonbit-community/NyaCSV](https://github.com/moonbit-community/NyaCSV): CSV parsing with quoted fields, custom delimiters, and streaming-friendly APIs.
- [moonbit-community/cmark](https://github.com/moonbit-community/cmark.mbt): A CommonMark parsing and rendering toolkit.
- [mizchi/markdown](https://github.com/mizchi/markdown.mbt): A lossless, incremental Markdown parser and compiler for editor workloads.
- [moonbit-community/XMLParser](https://github.com/moonbit-community/XMLParser): XML parsing for elements, attributes, comments, CDATA, and processing instructions.
- [moonbit-community/prettyprinter](https://github.com/moonbit-community/prettyprinter): A composable document-layout and pretty-printing library.
- [gmlewis/base64](https://github.com/gmlewis/moonbit-base64): A maintained Base64 encoder and decoder based on Go's implementation.
- [moonbit-community/flate](https://github.com/moonbit-community/flate): A runtime-agnostic, pure-MoonBit DEFLATE engine with gzip and zlib wrappers.
- [hustcer/fzip](https://github.com/hustcer/fzip): In-memory DEFLATE, gzip, zlib, and ZIP compression with streaming APIs and extensive security tests.
- Actively maintained ports of Go's checksum, hash, and compression libraries:
  - [gmlewis/crc32](https://github.com/gmlewis/moonbit-crc32)
  - [gmlewis/hash](https://github.com/gmlewis/moonbit-hash)
  - [gmlewis/gzip](https://github.com/gmlewis/moonbit-gzip)
  - [gmlewis/zlib](https://github.com/gmlewis/moonbit-zlib)
  - [gmlewis/md5](https://github.com/gmlewis/moonbit-md5): For compatibility, not security.
- [kawaz/grapheme](https://github.com/kawaz/grapheme.mbt): Unicode grapheme-cluster segmentation implementing UAX #29.
- [tonyfettes/unicode](https://github.com/moonbit-community/tonyfettes-unicode): Unicode 16 data and algorithms including normalization, IDNA, bidirectional text, and Punycode.
- [moonbit-community/fuzzy_match](https://github.com/moonbit-community/fuzzy_match): Fuzzy string matching and searching adapted from Jane Street's `fuzzy_match`.

### Application Development

- [moonbit-community/proton](https://github.com/moonbit-community/proton): A framework for native desktop applications with web frontends on Windows, macOS, and Linux.
- [moonbit-community/rabbita](https://github.com/moonbit-community/rabbita): A declarative, functional web UI framework formerly known as Rabbit-TEA.
- [tiye/respo](https://github.com/Respo/respo.mbt): A compact virtual-DOM library for browser applications.
- [mizchi/luna](https://github.com/mizchi/luna.mbt): An experimental declarative UI toolkit with virtual DOM, hydration, streaming rendering, and SSR/SSG companions.
- [oboard/mocket](https://github.com/oboard/mocket): A web framework supporting native and JavaScript backends.
- [mizchi/mars](https://github.com/mizchi/mars.mbt): A Hono-inspired web framework with trie routing, middleware, and server-sent events.
- [Yoorkin/rui](https://mooncakes.io/docs/Yoorkin/rui): Self-contained Vega-style UI components for Rabbita.
- [mizchi/tui](https://github.com/mizchi/tui.mbt): A reactive terminal user-interface library.

### Data Structures and Algorithms

- [dowdiness/alga](https://github.com/dowdiness/alga): Algebraic graphs with reusable traversal, cycle, topological-sort, and strongly-connected-component algorithms.
- [dowdiness/incr](https://github.com/dowdiness/incr): Incremental recomputation with automatic dependency tracking and durability-based verification.
- [Luna-Flow/linear-algebra](https://github.com/Luna-Flow/linear-algebra): Checked matrix and vector APIs with mutable and immutable dense representations.
- [Suquster/moonbit-pathfinding](https://github.com/Suquster/moonbit-pathfinding): Pathfinding and graph algorithms including BFS, Dijkstra, A*, JPS, contraction hierarchies, and hub labels.

### Systems and Interoperability

- [moonbit-community/tty](https://github.com/moonbit-community/tonyfettes-tty): Low-level native terminal state, standard handles, VT output, and input decoding.
- [moonbit-community/pty](https://github.com/moonbit-community/tonyfettes-pty): Cross-platform pseudo-terminal spawning integrated with `moonbitlang/async`.
- [justjavac/ffi](https://github.com/justjavac/moonbit-ffi): Tested UTF-8 C-string and UTF-16 wide-string conversions for FFI boundaries.
- [illusory0x0/native](https://github.com/moonbit-community/native): Native FFI utilities for pointer arithmetic, C strings and arrays, reference counting, and allocation.
- [mizchi/js](https://github.com/mizchi/js.mbt): JavaScript bindings for built-ins and browser, Node.js, Deno, and Bun APIs.
- [bikallem/webapi](https://github.com/bikallem/webapi): Type-safe Web Platform API bindings generated from WebIDL for the JavaScript and wasm-gc backends.
- [moonbit-community/sqlite3](https://github.com/moonbit-community/sqlite3.mbt): Lightweight, low-level bindings that provide a thin interface over the SQLite3 C API.
- [moonbit-community/postgres](https://github.com/moonbit-community/postgres.mbt): A PostgreSQL client library with an included connection pool.
- [mizchi/wit](https://github.com/mizchi/wit.mbt): A parser and resolver for WebAssembly Interface Types.
- [gmlewis/moonbit-pdk](https://github.com/gmlewis/moonbit-pdk): The actively maintained Extism plug-in development kit for MoonBit.

### Graphics and Media

- [bobzhang/colors](https://github.com/moonbit-community/colors): Color conversion and manipulation across RGB, linear RGB, XYZ, and LUV spaces.
- [mizchi/image](https://github.com/mizchi/image-mbt): Image codec primitives for PNG, BMP, JPEG, GIF, WebP, ICO, and AVIF, plus resizing.
- [Milky2018/wgpu_mbt](https://github.com/moonbit-community/wgpu-mbt): MoonBit bindings for the `wgpu-native` WebGPU API.
- [Milky2018/moon_rapier](https://github.com/moonbit-community/moon_rapier): A MoonBit port of the Rapier physics engine.
- [moonbit-community/diago](https://github.com/moonbit-community/diago): A diagram toolkit with D2-compatible input, multiple layout engines, and SVG or text output.

## Developer Tools

- [Moon](https://github.com/moonbitlang/moon): The official build system and package manager.
- [MoonLex](https://github.com/moonbitlang/moonlex): A lexer generator for MoonBit.
- [MoonYacc](https://github.com/moonbitlang/moonyacc): An LR(1) parser generator.
- [protoc-gen-mbt](https://github.com/moonbitlang/protoc-gen-mbt): Protocol Buffers code generation and runtime support.
- [tree-sitter-moonbit](https://github.com/moonbitlang/tree-sitter-moonbit): The official Tree-sitter grammar for MoonBit.
- [setup-moonbit](https://github.com/hustcer/setup-moonbit): A GitHub Action for installing and caching the MoonBit toolchain.
- [moonbit.nvim](https://github.com/moonbit-community/moonbit.nvim): MoonBit language support for Neovim.

## Showcase and Learning Projects

- [MoonBit Gallery](https://www.moonbitlang.com/gallery/): Editable browser demos including Tetris, Mario, Sudoku, Snake, and WASM-4 examples.
- [Build Your Own MoonBit](https://github.com/moonbitlang/BuildYourOwnMBT): An educational implementation of a small MoonBit-like language.
- [wasm5](https://github.com/moonbitlang/wasm5): A WebAssembly virtual machine written in MoonBit.
- [mbtcc](https://github.com/moonbitlang/mbtcc): A C11 compiler implemented in MoonBit.
- [MoonbitNES](https://github.com/moonbit-community/MoonbitNES): A Nintendo Entertainment System emulator written in MoonBit.

## Documentation and Learning

- [Official documentation](https://docs.moonbitlang.com/en/stable/): Language, standard-library, FFI, and toolchain documentation.
- [Interactive language tour](https://tour.moonbitlang.com/): Learn MoonBit in the browser.
- [MoonBit course](https://github.com/moonbitlang/moonbit-course): Official course materials and exercises.
- [Use and publish packages](https://docs.moonbitlang.com/en/stable/toolchain/moon/package-manage-tour.html): The official guide to Mooncakes and package management.
- [Build system tutorial](https://docs.moonbitlang.com/en/stable/toolchain/moon/tutorial.html): A practical introduction to modern MoonBit project workflows.

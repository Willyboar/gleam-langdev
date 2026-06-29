# Gleam LangDev

A curated collection of programming languages, compilers, interpreters, and language development tools written in **Gleam**.

<img src="https://img.shields.io/badge/Gleam-LangDev-2F2A36?style=for-the-badge&logo=gleam&logoColor=FFAFF3" alt="Awesome Gleam LangDev"/>

---

## Table of Contents

- [Languages](#languages)
- [Lexers](#lexers)
- [Parsers](#parsers)
- [Semantic Analysis](#semantic-analysis)
- [Type Systems](#type-systems)
- [Backends & Code Generation](#backends--code-generation)
- [Configuration Files](#configuration-files)
- [Error Reporting & Diagnostics](#error-reporting--diagnostics)
- [Source Positions & Spans](#source-positions--spans)
- [CLI Argument Parsing](#cli-argument-parsing)
- [Distribution & Packaging](#distribution--packaging)
- [Shell & System Operations](#shell--system-operations)
- [File I/O](#file-io)
- [Testing](#testing)
- [Data Formats](#data-formats)
- [Documentation & Markup](#documentation--markup)
- [Path Manipulation](#path-manipulation)
- [Contributing](#contributing)
- [License](#license)

---

## Languages

- **[eyg-lang](https://github.com/CrowdHailer/eyg-lang)** — A structural-typed scripting language with managed effects, designed as a safer bash/POSIX shell replacement
- **[bella](https://github.com/MystPi/bella)** — A simple functional programming language written in Gleam
- **[jet](https://github.com/i2y/jet)** — A dynamically typed OOP-functional hybrid language with Ruby-like syntax that runs on the BEAM
- **[spark](https://github.com/MystPi/spark)** — A compile-to-JS functional language built in Gleam
- **[rango](https://github.com/widici/rango)** — A compiled Lisp-like language targeting BEAM bytecode, written in Gleam
- **[example-lisp-interpreter](https://github.com/gleam-lang/example-lisp-interpreter)** — The official Gleam team's tree-walking Lisp interpreter example
- **[glisp](https://github.com/APConduct/glisp)** — A Lisp interpreter with a REPL, published as a Hex package
- **[gig](https://github.com/schurhammer/gig)** — A Gleam compiler written in Gleam that compiles Gleam source to C

## Lexers

- **[glexer](https://github.com/DanielleMaywood/glexer)** — A lexer for the Gleam language, written in Gleam
- **[just](https://github.com/GearsDatapacks/just)** — A JavaScript lexer and syntax highlighter for Gleam
- **[tear](https://gitlab.com/arkandos/tear)** — A lexer and syntax highlighter for Elixir
- **[pearl](https://github.com/GearsDatapacks/pearl)** — An Erlang lexer and syntax highlighter written in Gleam

## Parsers

- **[glance](https://github.com/lpil/glance)** — A permissive Gleam source code parser, written in Gleam
- **[splitter](https://github.com/lpil/splitter)** — Efficiently slice prefixes from strings, useful for building parsers
- **[nibble](https://github.com/hayleigh-dot-dev/nibble)** — A lexer and parser combinator library inspired by `elm/parser`
- **[chomp](https://github.com/MystPi/chomp)** — A fork of nibble with lexer step + parser combinators and custom error messages

## Semantic Analysis

- **[static_analyzer](https://github.com/MystPi/static_analyzer)** — A tiny static analyzer that detects unused and undefined variables in a Gleam subset

## Type Systems

- **[type_inference](https://github.com/MystPi/type_inference)** — An implementation of "Type Inference by Example" in Gleam
- **[simple_static_typechecker](https://github.com/MystPi/simple_static_typechecker)** — A minimal static typechecker built as a learning project

## Backends & Code Generation

- **[glove](https://github.com/Willyboar/glove)** — A Gleam library for generating QBE intermediate representation (IR) code
- **[gleam-wasm](https://github.com/gertvv/gleam-wasm)** — A proof-of-concept for compiling Gleam to WebAssembly (WAT format)

## Configuration Files

- **[tom](https://github.com/lpil/tom)** — A pure Gleam TOML parser
- **[yay](https://github.com/robertDurst/yay)** — Yet Another YAML parser for Gleam, supporting both Erlang and JavaScript targets

## Error Reporting & Diagnostics

- **[snag](https://github.com/lpil/snag)** — A boilerplate-free ad-hoc error type with contextual error chaining
- **[report](https://github.com/MystPi/report)** — Create informative, styled source code reports with annotations (inspired by codespan-reporting)

## Source Positions & Spans

- **[spanner](https://github.com/Willyboar/spanner)** — A small Gleam library for tracking positions and spans in source code, designed for use in lexers and parsers

## CLI Argument Parsing

- **[glint](https://github.com/TanklesXL/glint)** — Gleam CLI argument parsing with type-safe flags and automated help text
- **[clip](https://github.com/drewolson/clip)** — An applicative-style CLI option parser for Gleam

## Distribution & Packaging

- **[gleepack](https://github.com/yoshi-monster/gleepack)** — Pack a Gleam application into a standalone self-contained executable with a patched BEAM runtime

## Shell & System Operations

- **[shellout](https://github.com/tynanbe/shellout)** — A cross-platform library for shell operations and terminal styling in Gleam

## File I/O

- **[simplifile](https://github.com/bcpeinhardt/simplifile)** — Simple synchronous file/directory operations for Gleam, works on Erlang/Node/Deno/Bun

## Testing

- **[gleeunit](https://github.com/lpil/gleeunit)** — The standard test runner for Gleam, using EUnit on Erlang and a custom runner on JavaScript
- **[birdie](https://github.com/giacomocavalieri/birdie)** — Snapshot testing in Gleam, inspired by Rust's `insta`

## Data Formats

- **[gleam_json](https://github.com/gleam-lang/json)** — The official Gleam JSON library for encoding, parsing, and decoding JSON
- **[gsv](https://github.com/lpil/gsv)** — A simple CSV parser and serialiser for Gleam
- **[parsed_it](https://github.com/versecafe/parsed_it)** — Parsing and serialization for JSON and XML in Gleam, supporting both Erlang and JavaScript targets

## Documentation & Markup

- **[mork](https://codeberg.org/krig/mork)** — A Commonmark-compliant Markdown parser in pure Gleam, with GFM and Obsidian extensions, can output HTML
- **[jot](https://github.com/lpil/jot)** — A parser for Djot (a markup language like Markdown), can output HTML or parse to an AST


## Path Manipulation

- **[filepath](https://github.com/lpil/filepath)** — Cross-platform file path manipulation for Gleam (Unix and Windows)

---

## Contributing

Have a project to add? Open a PR or issue. 

## License

This project is licensed under [MIT](LICENSE).

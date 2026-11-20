# Oxide

Oxide is a hobby programming language written in Rust.

Oxide is an ongoing project where I'm exploring programming language design, compiler development, and how programming languages work under the hood.

The project is currently a work in progress, with the eventual goal of becoming a self-hosted language with its own build system.

## Repositories

Oxide is split across several repositories, each responsible for a different part of the language.


* [syntax](https://github.com/ThomasCarson81/syntax) - Shared token, AST and language structures
* [lexer](https://github.com/ThomasCarson81/lexer) - Lexical analysis and tokenisation
* [parser](https://github.com/ThomasCarson81/parser) - Parsing source code into an AST
* [semantic_analyser](https://github.com/ThomasCarson81/semantic_analyser) - Semantic analysis and validation
* [optimiser](https://github.com/ThomasCarson81/optimiser) - Code optimisation
* [interpreter](https://github.com/ThomasCarson81/interpreter) - Interpreting Oxide programs
* [compiler](https://github.com/ThomasCarson81/compiler) - Compiling Oxide into native code


## Goals

- Develop a programming language from scratch
- Implement a complete compiler pipeline
- Experiment with language design and type systems
- Explore LLVM for native code generation
- Build a language capable of compiling itself

## Status

Oxide is actively being developed and is not yet stable. Syntax, features, and internal design may change as development progresses.

## About

Oxide is a personal project developed as a way to learn more about compilers, programming language design, and systems programming.
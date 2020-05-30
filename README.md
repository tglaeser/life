## _Conway's Game of Life_ in Rust and WebAssembly
[rust-book]:https://doc.rust-lang.org/stable/book/
[rustwasm-book]:https://rustwasm.github.io/docs/book/
[rustup]:https://github.com/rust-lang/rustup/
[wasm-pack]:https://rustwasm.github.io/
[nodejs]:https://nodejs.org/
Based on the tutorial from the Rust 🦀 and WebAssembly 🕸 [book][rustwasm-book]; it demonstrates how to compile Rust sources
into WebAssembly to be served via [Node.js][nodejs].

[![Build Status](https://travis-ci.org/tglaeser/life.svg?branch=master)](https://travis-ci.org/tglaeser/life)

## 📚 Table of Contents
1. [Core sub-project](./core/README.md)
1. [Web sub-project](./web/README.md)

#### Prerequisites
This project requires [Rust][rust-book] to be installed via [`rustup`][rustup] as well as the [`wasm-pack`][wasm-pack] being
installed. To verify, run `wasm-pack --version`.

#### Get the Sources
```
$ git clone https://github.com/tglaeser/life.git
$ cd ./life
```
#### Displays the Project Structure
```
$ tree -L 3 .
.
├── core
│   ├── Cargo.toml
│   ├── README.md
│   ├── src
│   │   ├── lib.rs
│   │   └── utils.rs
│   └── tests
│       └── web.rs
├── LICENSE_APACHE
├── LICENSE_MIT
├── README.md
└── web
    ├── bootstrap.js
    ├── index.html
    ├── index.js
    ├── package.json
    ├── README.md
    ├── stylesheet.css
    ├── timer.js
    └── webpack.config.js
```

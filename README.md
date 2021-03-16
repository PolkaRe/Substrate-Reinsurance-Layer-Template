Experimental work on Polkadot Parachain for UnoRe platform


## Building This Book Locally

Building the book requires [mdBook], ideally the same version that
rust-lang/rust uses in [this file][rust-mdbook]. To get it:

[mdBook]: https://github.com/rust-lang-nursery/mdBook
[rust-mdbook]: https://github.com/rust-lang/rust/blob/master/src/tools/rustbook/Cargo.toml

```bash
$ cargo install mdbook --vers [version-num]
```
To build the book, type:

```bash
$ mdbook build
```

The output will be in the `book` subdirectory. To check it out, open up `book/index.html` in
a web browser, or to serve the book locally, type:

```bash
$ mdbook serve
```

The default address to view the book will be located at [http://localhost:3000](http://localhost:3000) .

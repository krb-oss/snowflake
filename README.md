# Snowflake

> Hash delta visualisation library.

## Introduction

This project is based on [snowflake](http://levien.com/snowflake.html) by Raph
Levein which is "an implementation for procedural generation of snowflakes."

## Building

This is a [Rust](https://www.rust-lang.org/) library and requires the
associated tooling be installed before proceeding. To build this library,
please run the following command from a Linux, Darwin or WSL terminal.

```bash
git clone git@github.com:krb-oss/snowflake.git ~/snowflake \
    && cd ~/snowflake \
    && cargo build
```

## Tests

Run the following command from within the project root.

```bash
cargo test
```

## License

[BSD](LICENSE) © [@KRB OSS](https://github.com/krb-oss)

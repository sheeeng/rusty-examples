# hello_world

## [Cargo.toml vs Cargo.lock](https://doc.rust-lang.org/cargo/guide/cargo-toml-vs-cargo-lock.html)

If you’re building a non-end product, such as a rust library that other rust [packages](https://doc.rust-lang.org/cargo/appendix/glossary.html#package) will depend on, put `Cargo.lock` in your `.gitignore`. If you’re building an end product, which are executable like command-line tool or an application, or a system library with crate-type of `staticlib` or `cdylib`, check `Cargo.lock` into git.

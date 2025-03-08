# Rust

## Rust Resources

Rust

- [The Rust Reference](https://doc.rust-lang.org/reference/)
- [Rust Ref: zh](https://rustwiki.org/zh-CN/reference/)
- ~~
- [The Rust Programming Language](https://doc.rust-lang.org/stable/book/)
- [The Rust Programming Language: Experiment Type](https://rust-book.cs.brown.edu/)
- [Rust 程序设计语言 (zh) - 2022](https://rustwiki.org/zh-CN/book/title-page.html)
- [Rust 程序设计语言 (zh) - 2024-05-02 ](https://kaisery.github.io/trpl-zh-cn/)
- ~~
- [effective rust: 35 Specific Ways to Improve Your Rust Code](https://effective-rust.com/)
- [effective-rust-cn](https://rustx-labs.github.io/effective-rust-cn/)
- ~~
- [The Rustonomicon: The Dark Arts of Unsafe Rust](https://doc.rust-lang.org/stable/nomicon/)
- [Rust 语言圣经(Rust Course)](https://course.rs/about-book.html)
- [rust-by-example](https://doc.rust-lang.org/rust-by-example/)
- [The Cargo Book](https://doc.rust-lang.org/cargo/index.html)
- [The Little Book of Rust Macros](https://veykril.github.io/tlborm/introduction.html)
- ~~
- [Rust RFCs - RFC Book](https://rust-lang.github.io/rfcs/introduction.html)
- ~~
- [releases](https://releases.rs/)
- [github releases](https://github.com/rust-lang/rust/releases)
- ~~
- [Rust 语言中文社区](https://rustcc.cn/)
- [clippy](https://doc.rust-lang.org/clippy/index.html)
- [Rust Design Patterns](https://rust-unofficial.github.io/patterns/)
- [Newtype Index Pattern](https://matklad.github.io/2018/06/04/newtype-index-pattern.html)
- [Embrace the newtype pattern -- Effective Rust](https://www.lurklurk.org/effective-rust/newtype.html)
- [Idiomatic tree and graph like structures in Rust](https://rust-leipzig.github.io/architecture/2016/12/20/idiomatic-trees-in-rust/)

Rust Compiler

- [cranelift: a fast, secure, relatively simple and innovative compiler backend](https://cranelift.dev/)
- [rustc_codegen_cranelift](https://github.com/rust-lang/rustc_codegen_cranelift/)
- [wasmtime: About
  A lightweight WebAssembly runtime that is fast, secure, and standards-compliant](https://github.com/bytecodealliance/wasmtime/)

Rust OS

- [NUDT-OS-Book](https://flying-rind.github.io/mini-Rust-os/)
- [rcore-os](https://github.com/rcore-os)
- [rCore-Tutorial-Book-v3](https://rcore-os.cn/rCore-Tutorial-Book-v3/chapter0/5setup-devel-env.html)
- [haibo_chen](https://ipads.se.sjtu.edu.cn/pub/members/haibo_chen)

Others

- [rust-for-linux](https://rust-for-linux.com/)
- [一文读懂什么是进程、线程、协程](https://www.cnblogs.com/Survivalist/p/11527949.html)
- [rust-cli](https://rust-cli.github.io/book/index.html)
- [Joel on Software](https://www.joelonsoftware.com/)

git submodule update --init --recursive

## Commands

```bash
# rustup: Install, manage, and update Rust toolchains.
rustup install/default/update/show

rustup self uninstall

# cargo: Rust's package manager and build system.
cargo new <project-name> # create a new Rust project

cargo build # build the current package
cargo run # build and run the current package
cargo check # check the current package for errors without building
cargo test # run the tests in the current package
cargo fmt # check formatting of the current package

cargo build --release # build the current package with optimizations

cargo doc --open # build all dependences doc and open in broswer

RUST_BACKTRACE=1 cargo run # checkout backtrace

```

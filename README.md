[![Clippy](https://github.com/nogibjj/rust-data-engineering/actions/workflows/lint.yml/badge.svg)](https://github.com/nogibjj/rust-data-engineering/actions/workflows/lint.yml)
[![Tests](https://github.com/nogibjj/rust-data-engineering/actions/workflows/tests.yml/badge.svg)](https://github.com/nogibjj/rust-data-engineering/actions/workflows/tests.yml)


# mini project 7: Rust CLI

In this project, we are going to execute rust CLI and compile with the general testing process. 

**Objectives**

This hands-on lab provides experience with:

- Forking and cloning a Rust project

- Modifying existing Rust code 

- Running `cargo build` and `cargo run`

- Version control with git

- Making a pull request (optional)

  
**Steps**

1. Fork the repository at **https://github.com/nogibjj/rust-data-engineering**

2. Clone your forked repository 

3. Navigate to one of the command-line tool [projects](caesar-cipher-cli/src/lib.rs)

4. Make a small modification to the tool: add a rust CLI

5. Run `cargo build` to compile your changes  

6. Run `cargo run` to test your modified tool

7. Commit your changes and push to your forked repository





### Technical Notes

## Makefile

Each subdirectory project uses this style to make it easy to test and run

```
format:
	cargo fmt --quiet

lint:
	cargo clippy --quiet

test:
	cargo test --quiet

run:
	cargo run 

all: format lint test run
```


## References

* [Rust Collections](https://doc.rust-lang.org/std/collections/index.html)
* [GitHub Copilot CLI](https://www.npmjs.com/package/@githubnext/github-copilot-cli)
* [Rust Fundamentals](https://github.com/alfredodeza/rust-fundamentals)
* [Rust Tutorial](https://nogibjj.github.io/rust-tutorial/)
* [Rust MLOps Template](https://github.com/nogibjj/mlops-template)

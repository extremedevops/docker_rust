# Rust

[![](https://badge.imagelayers.io/extremedevops/rust:latest.svg)](https://imagelayers.io/?images=extremedevops/rust:latest 'Get your own badge on imagelayers.io')

Rust is a systems programming language that runs blazingly fast, prevents nearly all segfaults, and guarantees thread safety.

**Featuring**

* zero-cost abstractions
* move semantics
* guaranteed memory safety
* threads without data races
* trait-based generics
* pattern matching
* type inference
* minimal runtime
* efficient C bindings

For more information please visit the rust website: [https://www.rust-lang.org/](https://www.rust-lang.org/)

### Docker image usage
This image contains a base installation of Rust so the best way to use it is to create a Dockerfile like the following to compile your source
```
FROM extremedevops/rust

ADD . /app

WORKDIR /app

CMD cargo run
```
As you can see this is a very basic example any suggestion for more examples is really appreciated.

### Feedback

Please report any issue or any suggestion [here](https://github.com/extremedevops/docker_rust/issues)

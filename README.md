# rust-labs

Rust learning sandbox.

## Getting Started

Ensure that Rust is installed on your system:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Follow the on-screen instructions to complete the installation.
Once installed, restart your terminal and verify the installation by running `rustc --version`.
You should see the version of the Rust compiler.

## Creating a New Rust Project

This project was created by running the command:

```bash
cargo new rust-labs
```

- `Cargo.toml`: The manifest file for Rust. It contains metadata for your project and dependencies.
- `src/main.rs`: The main source file for your project. By default, it contains a simple program that prints "Hello, world!".

## Compiling Rust programs

Rust projects are compiled with Cargo, Rust's package manager and build system.
To compile your project, run the following command in your project directory:

```bash
cargo build --bin binary1
```

```bash
cargo build --bin binary2
```

etc.

Cargo reads the `Cargo.toml` file, downloads the necessary dependencies, and compiles your project.
After successful compilation, Cargo places the executable in the `target/debug` directory.

## Running Rust programs

After compiling your project, you can run it using Cargo:

```bash
cargo run --bin binary1
```

```bash
cargo run --bin binary2
```

etc.

This command compiles your project (if it hasn't been compiled yet) and runs the resulting executable.

# Rust_Hello_World
The repository contains the steps to create the "Hello World" application in the README, along with an output image [hello_world.png](https://github.com/Murugan-Bounteous/Rust_Hello_World/blob/feed5eb44e7bee9aa3dd3375a27b188c409a4b7b/hello_world.png).

# Hello World in Rust

This repository contains a simple "Hello, World!" application written in Rust. Follow the steps below to set up and run the application on your machine.

## Table of Contents

- [Installation](#installation)
- [Creating the Project](#creating-the-project)
- [Running the Application](#running-the-application)
- [Conclusion](#conclusion)

## Installation

To get started, you need to install Rust. The recommended method is to use `rustup`. Open your terminal and run the following command:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

Follow the on-screen instructions to complete the installation. After installation, ensure your environment is updated by running:

```bash
source $HOME/.cargo/env
```

## Creating the Project

Once Rust is installed, you can create a new Rust project using Cargo, Rust's package manager and build system. Run the following command in your terminal:

```bash
cargo new hello_world
```

This will create a new directory called `hello_world` with the necessary project structure.

## Writing the "Hello, World!" Code

Change into your project directory:

```bash
cd hello_world
```

Open the `src/main.rs` file in your preferred text editor. The file should already contain the following code:

```rust
fn main() {
    println!("Hello, world!");
}
```

This code uses the `println!` macro to display "Hello, world!" in the terminal.

## Running the Application

To run your application, use the following command:

```bash
cargo run
```

You should see the output:

```
Hello, world!
```

## Conclusion

Congratulations! You've successfully created and run a "Hello, World!" application in Rust. From here, you can explore more features of Rust and start building more complex applications. Happy coding!

# Rust Programming

## Installation
1. Run the installation script by executing this command:

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh -s -- -y

```
2. Update your shell environment to immediately recognize the new paths without closing the window:
```
source "$HOME/.cargo/env"
```
3. Verify the installation by checking the versions of the compiler and package manager:
```
rustc --version
cargo --version
```

4. Update to latest rust components
```
rustup update
```

5. Open the local rust documentation
```
rustup doc
```

## First program

1. Create below files
```
mkdir hello_rust
touch main.rs
```

2. compile the file
```
rustc main.rs
./main
```

## Using cargo
1. Cargo new creates folder structure with dependencies
```
cargo new hello_cargo
```

2. Cargo build - compile the code
```
cargo build
```

3. Cargo run

```
cargo run
```

4. Check code for errors without producing an executable
```
cargo check
```

### Why Rust ?

 - Systems programmign language, helps you write fast and reliable software.
 - Stands out in combining high-level ergonomics + low level control
 - Rust makes it easy to write safe, expressive, and high level code by offering
    * Rich standard libraries
    * Powerful syntax
    * Comprehensive error messages


### Rust - Tools

 - Tools directly manages memory (performance and control are critical)

### Benefits
 
 #### For Students:
 - Excellent choice for learning systems programming
 - Access to great documentation
 - Community support
 - Practical learning -> safety, memory and systems programming

 #### Professionals :
 - Reliable code -> strict compiler boosts safety and code quality
 - Performance -> Rust's C/C++ like performance suits high-efficiency apps
 - Modern tooling -> Cargo, rustfmt, rust-analyzer boost productivity

### Industry leaders

 - Mozilla was by using rust
 - Coursera -> for data processing
 - Dropbox -> parts 
 - Figma
 - Microsoft - safety and faster systems programming

### Key features

 - Rust was designed with a focus on -> Safety, Performance and Concurrency

#### Memory Safety
- Rust manages memory without a garbage collector
- Rust enforces ownership rules at compile time
- Ownership: each piece of data in rust has a single owner
- Borrowing: references can be created without owning the data
- Lifetimes: these ensure that references always valid

#### Concurrency
 - Writing programs that can do multiple things at the same time.
 - Can be tricky -> multiple threads can access same data
 - Rust solves this by ensuring safe multithreaded access, catching potential issues at compile time


#### Performace
 - Offers low-level control over memory and other resources
 - Critical for writing high-performance applications


#### Rust philosophy -> safe and fast


### Tooling and Ecosysten
1. Cargo: 
    - Rust's build system and package manager
    - It manages dependencies and builds
2. rustfmt
    - formats code for consistency and readability
3. rust-analyzer
    - It is a IDE tool offering code completion and inline errors for efficient coding


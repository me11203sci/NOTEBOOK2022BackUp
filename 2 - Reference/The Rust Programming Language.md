**Author:** [[Steve Klabnik]] and [[Carol Nichols]] 
**Tags:** #Programming #Rust #Extracurricular
**Uniform Resource Locator:**  [https://doc.rust-lang.org/book/](https://doc.rust-lang.org/book/)

---
### 1.1 Installation
Use `rustup` to install updates.

### 1.2 Hello, World!
Some notes on the the anatomy of the following Rust program:
```rust
fn main()
{
	println!("Greetings.");
}
```
- `fn main()` is the function signature, where the `fn` keyword denotes a function. Additionally, much like Java and C `main` is a special function and is the first thing to be executed at runtime.
- Rust requires `{}` wrapped around the function body.
- `!` calls a macro as opposed to a function.
- `;` denotes the end of an expression.

Similar to C++ and C, Rust compilation and execution are two separate steps.
- `rustc` complies a `.rs` file and outputs a binary executable.

### 1.3 Hello, Cargo!
Cargo is Rust's package manager. It is used to handle dependencies and as such it is advised to start more complex projects through cargo.
- Invoking the `new` creates a new directory containing `Cargo.toml`, and a `src` directory. Additionally, the file is automatically initialized as a repository and the version control software can be specified via the `--vsc` flag.
- **\*.toml**: Tom's Obvious, Minimal Language.

To build a project, use the `build` command from the top level project directory.
- This outputs an executable to `/target/debug`.
- Creates `cargo.lock`, which keeps track of dependency versions.
- `check` just checks for errors and does not create an executable.
- `run` complies a cargo project and runs the resulting executable.

### 3.1 Variables and Mutability
By default variables in Rust are immutable, however the language provides the freedom to make them mutable if you so choose.
```Rust
let x = 2;
let mut y = 4; // Mutable variable
```
- `let` keyword declares a variable.
- `mut` keyword designates a variable as mutable.
- The trade-off between these two options is between performance and memory safety.

Constants make use of the `const` keyword and unlike variables cannot be modified using the `mut` keyword.
	- Additionally, .
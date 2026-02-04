# Rust Up Man (Rustlings)

Small Rust exercises to help you learn the Rust programming language. No setup. No installation. No hassle.

## Getting Started

### Prerequisites

- [Rust](https://www.rust-lang.org/tools/install) (1.70.0 or higher)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/rustlings.git
cd rustlings
```

2. Build the exercises:
```bash
cargo build
```

### Running Exercises

Run a specific exercise:
```bash
cargo run --bin intro1
```

Test a specific exercise:
```bash
cargo test --bin intro1
```

Test all exercises:
```bash
cargo test
```

## Exercise List

| Exercise | Topic | Description |
|----------|-------|-------------|
| 00_intro | Introduction | Basic Rust syntax and printing |
| 01_variables | Variables and Mutability | Working with mutable and immutable variables |
| 02_functions | Functions | Defining and calling functions |
| 03_if | Control Flow | If statements and conditional logic |
| 04_primitive_types | Primitive Types | Basic data types in Rust |
| 05_vecs | Vectors | Working with vector collections |
| 06_move_semantics | Move Semantics | Ownership and borrowing basics |
| 07_structs | Structs | Defining and using structs |
| 08_enums | Enums | Enum types and pattern matching |
| 09_strings | Strings | String manipulation |
| 10_modules | Modules | Code organization with modules |
| 11_hashmaps | HashMaps | Key-value data structures |
| 12_options | Options | Handling optional values |
| 13_error_handling | Error Handling | Result types and error management |
| 14_generics | Generics | Generic programming |
| 15_traits | Traits | Defining and implementing traits |
| 16_lifetimes | Lifetimes | Lifetime annotations |
| 17_tests | Testing | Writing and running tests |
| 18_iterators | Iterators | Working with iterators |
| 19_smart_pointers | Smart Pointers | Box, Rc, Arc, Cow pointers |
| 20_threads | Threads | Concurrent programming |
| 21_macros | Macros | Creating and using macros |
| 22_clippy | Clippy | Using Rust's linter |
| 23_conversions | Conversions | Type conversions and casting |
| quizzes | Quizzes | Mid-course knowledge checks |

## Learning Path

The exercises are arranged in approximate order of difficulty:

**Beginner (00-09):**
- Intro to Rust syntax
- Variables and functions
- Control flow and basic types
- Collections and strings

**Intermediate (10-16):**
- Advanced data structures
- Error handling
- Generics and traits
- Lifetime management

**Advanced (17-23):**
- Testing and iteration
- Smart pointers and concurrency
- Macros and type conversions

## How to Use

1. Start with `intro1.rs` to get familiar with the exercise format
2. Work through exercises in numerical order
3. Each exercise contains:
   - Instructions and explanations
   - Incomplete code that needs fixing
   - Tests to verify your solution

## Development Tools

### Formatting
```bash
cargo fmt
```

### Linting with Clippy
```bash
cargo clippy
```

### Auto-fix Clippy suggestions
```bash
cargo clippy --fix
```


## Learning Resources

- [The Rust Programming Language Book](https://doc.rust-lang.org/book/)
- [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
- [Rust Standard Library Documentation](https://doc.rust-lang.org/std/)
- [Rustlings Official Repository](https://github.com/rust-lang/rustlings)


## Acknowledgments

Based on the original [rust-lang/rustlings](https://github.com/rust-lang/rustlings) project, which provides an excellent way to learn Rust through hands-on exercises.
# 🔍 Mini-Grep (Rust)

A minimal implementation of the classic `grep` command-line utility, written in [Rust](https://www.rust-lang.org/).  
This project reads a file and searches for lines that match a given query string, with optional case-insensitive search.

---

## 📌 Features

- Simple command-line interface
- Efficient file reading and line-by-line search
- Case-sensitive and case-insensitive search modes
- Error handling for invalid inputs and missing files
- Written entirely in idiomatic Rust

---

## 💻 Usage

```bash
# Basic usage
cargo run -- <query> <filename>

# Example
cargo run -- rust poem.txt

# Case-insensitive search
CASE_INSENSITIVE=1 cargo run -- rust poem.txt

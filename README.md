# minigrep

A simple command-line tool written in Rust for searching for a query string in a file. Inspired by the classic `grep` utility, `minigrep` is a lightweight alternative for basic search needs.

## Features

- Search for a string in a text file
- Case-sensitive and case-insensitive search modes
- Simple and easy-to-understand codebase

## Usage

```bash
cargo run -- <QUERY> <FILENAME>
```
Example:

```bash
cargo run -- to poem.txt
To run in case-insensitive mode, set the CASE_INSENSITIVE environment variable:
```
bash
CASE_INSENSITIVE=1 cargo run -- to poem.txt
Building
To build the project, ensure you have Rust installed, then run:

bash
cargo build
Running Tests
You can run the tests using:

bash
cargo test

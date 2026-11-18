# Rust CSV Data Validator

A command-line program that checks a CSV file for missing fields and duplicate IDs, then prints a summary.

## Requirements
- Rust stable toolchain

## Run
```bash
cargo run -- sample.csv
```

## CSV format
The first row must be:
```csv
id,name,email
```
Each following row should contain all three fields. IDs should be unique.

## Tests
```bash
cargo test
```

## What I learned
Rust ownership, error handling, iterators, parsing text files, and writing testable command-line programs.

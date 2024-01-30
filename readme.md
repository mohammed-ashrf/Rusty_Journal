# Rusty Journal 0.1.0

Rusty Journal is a sleek and efficient command-line to-do app written in Rust. Manage your tasks effortlessly with a minimalist interface, providing a seamless experience for organizing your daily activities.

## Features

- **Simple Usage**: Navigate through your to-do list effortlessly with intuitive commands.
- **Custom Journal File**: Easily switch between journal files using the `-j` or `--journal-file` option.
  
## Installation

To get started, clone the repository and build the Rusty Journal executable:

```bash
git clone https://github.com/your-username/rusty-journal.git
cd rusty-journal
cargo build --release
```
## Usage

```bash
rusty-journal [OPTIONS] <SUBCOMMAND>
```

## Options

`-h, --help`: Prints help information.
`-V, --version`: Prints version information.
`-j, --journal-file <journal-file>`: Use a different journal file.

## Subcommands

1. add: Write tasks to the journal file.
2. done: Remove an entry from the journal file by position.
3. help: Prints this message or the help of the given subcommand(s).
4. list: List all tasks in the journal file.

## Getting Started

1. Add a Task: Use the `add` subcommand to add tasks to your journal.

```bash
rusty-journal add "Complete Rust tutorial"
```
2. Mark as Done: Once a task is completed, use the `done` subcommand to remove it from the journal.

```bash
rusty-journal done 1
```
3. List Tasks: View all tasks in your journal with the `list` subcommand.

```bash
rusty-journal list
```
4. Custom Journal File: If you prefer using a specific journal file, utilize the `-j` or `--journal-file`option.

```bash
rusty-journal -j path/to/custom_journal.toml list
```

## License

This project is licensed under the MIT License.

<hr>
Happy organizing with Rusty Journal! 📝
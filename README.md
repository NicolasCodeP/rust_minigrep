# Minigrep

Minigrep is a simple command-line text search tool written in Rust. It mimics the basic functionality of the classic `grep` utility, allowing you to search for a string within a file.

## Features

- Search for a specific string in a file
- Case-sensitive and case-insensitive search
- Simple and easy-to-understand implementation

## Installation

To build and install Minigrep, you'll need to have Rust and Cargo installed on your system. You can download them from [rust-lang.org](https://www.rust-lang.org/).

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/minigrep.git
   cd minigrep
   ```

2. Build the project:

   ```bash
   cargo build --release
   ```

3. Run the executable:

   ```bash
   ./target/release/minigrep [OPTIONS] <QUERY> <FILENAME>
   ```

## Usage

Run Minigrep with the search query and the file you want to search in:

```bash
minigrep <QUERY> <FILENAME>
```

### Options

- `-i`, `--ignore-case`: Perform a case-insensitive search.

## Examples

1. Case-sensitive search:

   ```bash
   minigrep "search_term" example.txt
   ```

2. Case-insensitive search:

   ```bash
   minigrep -i "search_term" example.txt
   ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

Inspired by the Rust book's minigrep project.

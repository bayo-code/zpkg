# ZPKG - A Zig package manager
The purpose of this project is to create a package manager that makes managing code and dependencies easier for zig projects.

My goal is to create a package manager for zig that is as feature-rich and powerful as the `cargo` package manager for Rust, so that is my inspiration.

The package manager will be responsible for:
* Downloading zig project dependencies and compiling the project
* Publishing a zig project to the zpkg registry
* Managing versioning

## Architecture
The general design of the project is specified here at [architecture.md](architecture.md)

## Requirements
You need to have the zig compiler installed to build this package manager.

## How To Build
Clone the repository:
```sh
git clone https://github.com/bayo-code/zpkg
```

Build the project:
```sh
zig build install -Drelease-fast=true
```

## License
This project is licensed under the MIT License.

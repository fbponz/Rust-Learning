This folder contains the projects of the book "The Rust Programming Language"

# Tools included in Rust
## Automatic Formatting with rustfmt

To install rustfmt:

	$ rustup component add rustfmt

apply formatting for the all crate

	$ cargo fmt

## Common mistakes and improve code.

To install Clippy

	$ rustup component add clippy

To run clippy for all the crate

	$ cargo clippy

# Usage of Cargo
## Creating a project with cargo
This create creates a package with toml file that contains the package configuration and dependencies.

	$ cargo new {name_cargo}
	$ cd {name_cargo}

## Building and running a cargo project
To build the cargo package

	$cargo build

To build the cargo package with release profile

	$cargo build --release

To run the cargo package

	$cargo run

To check the cargo package
	
	$cargo check

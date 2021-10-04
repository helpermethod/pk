# pk

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/helpermethod/pk/main/LICENSE)

`pk` (short for: `process kill`) is a shell script for killing a process by TCP listen port number.

## Installation

    curl -sSL https://raw.githubusercontent.com/helpermethod/pk/main/pk > "$HOME"/bin/pk && chmod +x "$HOME"/bin/pk

Make sure to add `$HOME/bin` to your `PATH`.

## Usage

To `kill` (interrupt) the `process` listening on port `8080` type

    pk 8080

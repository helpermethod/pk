# pk

`pk` is a shell script which allows you to kill a process by TCP listen port number.

## Installation

    curl -sSL https://raw.githubusercontent.com/helpermethod/pk/main/pk > "$HOME"/bin/pk && chmod +x "$HOME"/bin/pk

Make sure to add `$HOME/bin` to your `PATH`.

## Usage

To kill/interrupt the application listening on port `8080`, type

    pk 8080

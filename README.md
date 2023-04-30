# STEAMWORLD EXTRACTOR

A extractor/compressor tool to handle SteamWorld compressed files.

## Games supported

- SteamWorld Dig 2
- SteamWorld Heist
- SteamWorld Quest Hand of Gilgamech

## Getting Started

### Requirements

- Python >= 3.9
- Poetry

### How to use poetry

```sh
# to install dependencies
$ poetry install

# to use python with dependencies
$ poetry shell
$ python

# to exit poetry shell
$ exit
```

### Testing

```sh
# inside poetry shell
$ pytest ./
```

### Others

```sh
# Formatting and linting will run at git commit
# however you can run it at will (inside poetry shell)

# Formatting
$ black ./

# Linting
$ flake8 ./
```

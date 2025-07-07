# bash scripts

> a collection of bash-scripts

## link

links the scripts to ~/bin

### Usage

```bash
./link
```

## cmphash

compares the hash of file to the ash

### Usage

```bash
cmphash [-m algorithm] [FILE] [HASH]
```

## up

Runs series of updates

- apt { update, upgrade, autoremove, clean }
- flatpak
- homebrew {update, upgrade, autoremove}
- asdf { plugins }
- atuin
- rust { rustup, rust }
- cargo
- platformio
- nvm { node }
- npm
- pnpm { self, packages }

### usage

```bash
up
```

## makescript

Creates a empty bashscript with Shebang and 755 mod, and opens it in nvim.

Usage:

```bash
makescript [FILENAME]
```

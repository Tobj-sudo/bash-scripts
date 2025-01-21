# bash scripts

> a collection of bash-scripts

## link

links the scripts to ~/bin

## cmphash

compares the hash of file to the ash

### Usage

```
cmphash [-m algorithm] [FILE] [HASH]
```

## up

Runs series of updates

- apt { update, upgrade, autoremove, clean }
- flatpak { update, remove unused}
- asdf { self, plugins }
- atuin
- rust { rustup, rust }
- cargo
- platformio
- homebrew


## makescript

Creates a empty bashscript with Shebang and 755 mod, and opens it in nvim.

Usage:
```
makescript [ FILENAME ]
```

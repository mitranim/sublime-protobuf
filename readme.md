## Overview

Initial sketch for a Sublime Text syntax for Protocol Buffers (Protobuf). Written in [SBNF](https://github.com/BenjaminSchaaf/sbnf).

  * Source file: `proto.sbnf`.
  * Auto-generated syntax: `proto.sublime-syntax`.

Incomplete, but already much more usable than the existing alternatives on Package Control.

## Installation

Clone the repo and symlink it to your Sublime packages directory. Example for MacOS:

```sh
git clone https://github.com/mitranim/sublime-protobuf.git
cd sublime-protobuf
ln -sf "$(pwd)" "$HOME/Library/Application Support/Sublime Text 3/Packages/"
```

To find the packages directory on your system, use Sublime Text menu → Preferences → Browse Packages.

## License

https://unlicense.org

## Misc

I'm receptive to suggestions. If this package _almost_ satisfies you but needs changes, open an issue or chat me up. Contacts: https://mitranim.com/#contacts

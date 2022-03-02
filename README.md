dmenu

- [Patches](https://tools.suckless.org/dmenu/patches/)
    - dmenu-center-20200111-8cd37e1.diff
    - dmenu-fuzzyhighlight-4.9.diff

# dmenu - dynamic menu

dmenu is an efficient dynamic menu for X.

## Requirements

In order to build dmenu you need the Xlib header files.

## Installation

Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):
```bash
make clean install
```

## Running dmenu

See the man page for details.


# bab - AUR Package

This repository contains the AUR (Arch User Repository) package for [bab](https://github.com/bab-sh/bab), a simple task runner for your projects.

## Installation

### From AUR

```bash
yay -S bab
# or
paru -S bab
```

### Manual Installation

```bash
git clone https://github.com/bab-sh/aur-bab.git
cd aur-bab
makepkg -si
```

## Building

The PKGBUILD downloads the source code from the [main repository](https://github.com/bab-sh/bab) release tags.

To build:
```bash
makepkg
```

To build and install:
```bash
makepkg -si
```

## Maintainer

Sebastian Stepper <sebastian-stepper@gmx.de>

## Links

- [Main Repository](https://github.com/bab-sh/bab)
- [AUR Package](https://aur.archlinux.org/packages/bab) (when published)
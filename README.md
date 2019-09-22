# Dotfiles

Various config files (git, vim, zsh).

## Prerequisites

Install (GNU stow)[https://www.gnu.org/software/stow/] to handle symlinks.
```bash
sudo apt-get install stow
```

## Installation
Clone repository:
```bash
git clone git@github.com:jcsongor/dotfiles.git
```

Symlink modules to $HOME using GNU stow
```bash
stow <package>
```

Reload config if needed (e.g.: `. ~/.zshrc`)


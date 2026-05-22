# Setup

## System Packages
```sh
# Arch
sudo pacman -S neovim gcc git ripgrep fd unzip make

# macOS (Homebrew)
brew install neovim gcc git ripgrep fd unzip make

# Ubuntu/Debian
sudo apt install neovim gcc git ripgrep fd-find unzip make
```

## Rust
```sh
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

## Bun (replaces Node.js)
```sh
curl -fsSL https://bun.sh/install | bash
```

## Nerd Font
Download from [nerdfonts.com](https://www.nerdfonts.com/) (e.g. JetBrainsMono, FiraCode) and set it in your terminal.

## Neovim Config
```sh
git clone git@github.com:ancxanas/nvim-config.git ~/.config/nvim
nvim
```

Then within Neovim, run `:Lazy` and `:Mason` to let everything install.

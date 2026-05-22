# nvim-config

Personal Neovim configuration based on [kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim).

## Features

- **Languages:** JavaScript/TypeScript, Rust, C, Lua
- **LSP:** `ts_ls`, `rust-analyzer`, `clangd`, `lua-language-server`
- **Formatting:** `prettier`, `rustfmt`, `clang-format`, `stylua` (auto-format on save)
- **Completion:** `blink.cmp` with LuaSnip snippets
- **Fuzzy finding:** Telescope with fzf-native
- **File explorer:** Neo-tree (toggle with `\`)
- **Colorscheme:** TokyoNight (night)
- **Git:** Gitsigns with inline blame and hunk staging
- **Autopairs, indent guides, todo comments, and more**

## Requirements

- Neovim >= 0.11
- `git`, `make`, `unzip`, C compiler (`gcc`)
- [ripgrep](https://github.com/BurntSushi/ripgrep)
- Nerd Font (for icons)

## Install

```sh
git clone git@github.com:ancxanas/nvim-config.git ~/.config/nvim
nvim
```

Run `:Lazy` to check plugin status, `:Mason` for LSP/tool status.

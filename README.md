# LazyVim

Neovim config for the lazy powered by [💤 lazy.nvim](https://github.com/folke/lazy.nvim).

Can't decide between building a config from scratch or using one of the existing
Neovim **_distros_**?

With **LazyVim** you don't have to. Configuring **LazyVim** is
**exactly the same** as you would configure a config from scratch.
You can easily add new plugins, change the config for existing ones
or disable plugins.

![image](https://user-images.githubusercontent.com/292349/210136312-c211f781-6d51-46b0-a265-6098bdbb364d.png)

## 🚀 Getting Started

You can find a starter template for **LazyVim** [here](https://github.com/LazyVim/starter)

**TLDR:**

```lua
require("lazy").setup({
  spec = {
    -- import LazyVim plugins
    { "LazyVim/LazyVim", import = "lazyvim.plugins" },
    -- import/override with your plugins
    { import = "plugins" },
  },
  defaults = {
    lazy = true, -- every plugin is lazy-loaded by default
    version = "*", -- try installing the latest stable version for plugins that support semver
  },
})
```

## ✅ Todo

- [ ] documentation
- [x] treesitter auto-install seems broken. Switch to `ensure_installed` instead?
- [x] list all plugins in readme
- [ ] test all-the-things

<!-- plugins:start -->

## Plugins

- [alpha-nvim](https://github.com/goolord/alpha-nvim)
- [catppuccin](https://github.com/catppuccin/nvim)
- [cmp-buffer](https://github.com/hrsh7th/cmp-buffer)
- [cmp-emoji](https://github.com/hrsh7th/cmp-emoji)
- [cmp-nvim-lsp](https://github.com/hrsh7th/cmp-nvim-lsp)
- [cmp-path](https://github.com/hrsh7th/cmp-path)
- [cmp_luasnip](https://github.com/saadparwaiz1/cmp_luasnip)
- [dressing.nvim](https://github.com/stevearc/dressing.nvim)
- [flit.nvim](https://github.com/ggandor/flit.nvim)
- [friendly-snippets](https://github.com/rafamadriz/friendly-snippets)
- [gitsigns.nvim](https://github.com/lewis6991/gitsigns.nvim)
- [indent-blankline.nvim](https://github.com/lukas-reineke/indent-blankline.nvim)
- [lazy.nvim](https://github.com/folke/lazy.nvim)
- [LazyVim](https://github.com/LazyVim/LazyVim)
- [leap.nvim](https://github.com/ggandor/leap.nvim)
- [lualine.nvim](https://github.com/nvim-lualine/lualine.nvim)
- [LuaSnip](https://github.com/L3MON4D3/LuaSnip)
- [mason-lspconfig.nvim](https://github.com/williamboman/mason-lspconfig.nvim)
- [mason.nvim](https://github.com/williamboman/mason.nvim)
- [mini.ai](https://github.com/echasnovski/mini.ai)
- [mini.bufremove](https://github.com/echasnovski/mini.bufremove)
- [mini.comment](https://github.com/echasnovski/mini.comment)
- [mini.indentscope](https://github.com/echasnovski/mini.indentscope)
- [mini.pairs](https://github.com/echasnovski/mini.pairs)
- [mini.surround](https://github.com/echasnovski/mini.surround)
- [neo-tree.nvim](https://github.com/nvim-neo-tree/neo-tree.nvim)
- [neoconf.nvim](https://github.com/folke/neoconf.nvim)
- [neodev.nvim](https://github.com/folke/neodev.nvim)
- [noice.nvim](https://github.com/folke/noice.nvim)
- [nui.nvim](https://github.com/MunifTanjim/nui.nvim)
- [null-ls.nvim](https://github.com/jose-elias-alvarez/null-ls.nvim)
- [nvim-bufferline.lua](https://github.com/akinsho/nvim-bufferline.lua)
- [nvim-cmp](https://github.com/hrsh7th/nvim-cmp)
- [nvim-lspconfig](https://github.com/neovim/nvim-lspconfig)
- [nvim-navic](https://github.com/SmiteshP/nvim-navic)
- [nvim-notify](https://github.com/rcarriga/nvim-notify)
- [nvim-spectre](https://github.com/windwp/nvim-spectre)
- [nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter)
- [nvim-treesitter-textobjects](https://github.com/nvim-treesitter/nvim-treesitter-textobjects)
- [nvim-ts-context-commentstring](https://github.com/JoosepAlviste/nvim-ts-context-commentstring)
- [nvim-web-devicons](https://github.com/nvim-tree/nvim-web-devicons)
- [persistence.nvim](https://github.com/folke/persistence.nvim)
- [plenary.nvim](https://github.com/nvim-lua/plenary.nvim)
- [telescope.nvim](https://github.com/nvim-telescope/telescope.nvim)
- [todo-comments.nvim](https://github.com/folke/todo-comments.nvim)
- [tokyonight.nvim](https://github.com/folke/tokyonight.nvim)
- [trouble.nvim](https://github.com/folke/trouble.nvim)
- [vim-illuminate](https://github.com/RRethy/vim-illuminate)
- [vim-startuptime](https://github.com/dstein64/vim-startuptime)
- [which-key.nvim](https://github.com/folke/which-key.nvim)

<!-- plugins:end -->

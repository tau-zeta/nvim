<p align="center">
<img src="assets/nvim-header.png" alt="Neovim Config Header" width="400">
</p>

---

#### Configs may change, But these settings will always remain the same:
```lua
-- Global Variables
vim.g.mapleader = " "
vim.g.localleader = " "


-- Options
vim.opt.number = true
vim.opt.relativenumber = true
vim.opt.cmdheight = 0
vim.opt.signcolumn = 'yes'
vim.opt.updatetime = 250
vim.opt.timeoutlen = 300
vim.opt.splitright = true
vim.opt.splitbelow = true
vim.opt.list = true
vim.opt.listchars = { tab = ' ', trail = ' ', nbsp = '␣' }
vim.opt.fillchars = { eob = ' ' }
vim.opt.mouse = 'a'
vim.opt.cursorline = true
vim.opt.termguicolors = true
vim.opt.showmode = false
vim.opt.clipboard = 'unnamedplus'
vim.opt.wrap = false
vim.opt.tabstop = 2
vim.opt.shiftwidth = 2
vim.opt.swapfile = false
vim.opt.inccommand = 'split'
vim.opt.scrolloff = 10
vim.opt.breakindent = true
vim.opt.ignorecase = true
vim.opt.smartcase = true
vim.opt.winborder = 'rounded'

vim.diagnostic.config({ virtual_text = true })

-- Keymaps
vim.keymap.set('n', '<leader>w', ':write<CR>')
vim.keymap.set('n', '<leader>q', ':quit<CR>')
vim.keymap.set('n', '<leader>f', ':Pick files<CR>')
vim.keymap.set('n', '<leader>h', ':Pick help<CR>')
vim.keymap.set('n', '<leader>g', ':Pick grep_live<CR>')
```



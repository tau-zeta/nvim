<p align="center">
  NEOVIM CONFIG
</p>

---

* Minimal plugins installed
* LSPs must be updated manually by following these steps,
  1. Make sure executable for LSPs are installed.
  2. Go to the [nvim-lsp-config Github repository](https://github.com/neovim/nvim-lspconfig), navigate to `/nvim-lspconfig/lsp` and look for required lsp. (eg. `pyright.lua`)
  3. Copy and paste the contents of required lsp file contents into neovim config folder under `~/.config/nvim/lsp/`
  4. Enable the lsp from `init.lua`. (eg.`vim.lsp.enable({ 'pyright' })`)


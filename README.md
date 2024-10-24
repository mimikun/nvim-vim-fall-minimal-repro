# nvim-vim-fall-minimal-repro

## How to reproduce

```bash
cd ~/.config
git clone https://github.com/mimikun/nvim-vim-fall-minimal-repro.git
export NVIM_APPNAME="nvim-vim-fall-minimal-repro"
# or if you use fish-shell
# set -Ux NVIM_APPNAME nvim-vim-fall-minimal-repro
nvim -u NORC -c "source https://raw.githubusercontent.com/nvim-neorocks/rocks.nvim/master/installer.lua"
# NOTE: install phase question 
# Set up luarocks (recommended) ?: false
# NEED set false, because an error occurs.
```

after neovim launch

Run `:Rocks sync`, and `Fall file`

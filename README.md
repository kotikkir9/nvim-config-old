# Neovim config

This config is inspired by ThePrimegen's "Neovim RC From Scratch". 

I'm still working on to make it tailored to my workflow.

```
git clone https://github.com/kotikkir9/nvim-config.git ~/.config/nvim/
```

```
Note: ripgrep need to be installed on the system, else the grep-keymap won't work.
```

Clone Packer repo:
```
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```

Open packer.lua file and execute the source file:
```
lua/thekirill/packer.lua
:so
```

Install plugins:
```
:PackerSync
```

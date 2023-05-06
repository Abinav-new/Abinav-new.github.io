---
title: "Lazyvim Setup"
date: 2023-05-06T02:35:09Z
---
# how to setup lazyvim on android using termux
```
# required
mv ~/.config/nvim ~/.config/nvim.bak

# optional but recommended
mv ~/.local/share/nvim ~/.local/share/nvim.bak
mv ~/.local/state/nvim ~/.local/state/nvim.bak
mv ~/.cache/nvim ~/.cache/nvim.bak
git clone https://github.com/LazyVim/starter ~/.config/nvim
rm -rf .config/nvim/.git
nvim

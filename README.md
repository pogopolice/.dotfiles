# .dotfiles
Configuration files for Arch Linux with ZSH

## ZSH Packages
Install these packages
fzf
git
less
stow
tmux
zsh
starship
ttf-meslo-nerd

## NeoVim Packages
neovim
xclip
git
make
unzip
gcc
ripgrep

## TypeScript Packages
npm

## NeoVim Kickstart
git clone https://github.com/nvim-lua/kickstart.nvim.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim

## Installation
Clone this project into your home directory
git clone --recurse-submodules https://github.com/pogopolice/.dotfiles.git
stow .

# .dotfiles
Configuration files for Arch Linux with ZSH

## ZSH Packages
### Install these packages
fzf
git
less
stow
zsh
starship
ttf-meslo-nerd

## Tmux Packages
tmux
ncurses

## NeoVim Packages
neovim
xclip
git
make
unzip
gcc
ripgrep
fd

### Python
python-pip
python-neovim

### TypeScript Packages
npm
- mkdir ~/.npm-packages
- npm config set prefix ~/.npm-packages
- npm install -g neovim

## Installation
### Clone this project into your home directory
- git clone --recurse-submodules https://github.com/pogopolice/.dotfiles.git
- stow .


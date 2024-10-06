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

## AWS CLI
### Prerequisites
unzip
glibc
groff
less

### AWS CLI Install
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
- unzip awscliv2.zip
- sudo ./aws/install
- rm -rf awscliv2.zip
- aws configure sso

### AWS CDK Install
- npm install -g aws-cdk

## GIT
git config --global user.name "USER NAME"
git config --global user.email "USER@EMAIL"
git config --global init.defaultBranch main

## Install dotfiles
### Clone this project into your home directory
- git clone --recurse-submodules https://github.com/pogopolice/.dotfiles.git
- stow .

### Change Default Shell
chsh -s $(which zsh)


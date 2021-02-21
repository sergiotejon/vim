# Instalation

git clone ~/.vim 

Para MAC:
brew tap homebrew/cask-fontsi && \
brew cask install font-hack-nerd-font

Para Linux:
Download https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/Hack.zip
mkdir ~/.local/share/fonts
Unzip
fc-cache -f -v

cd ~
ln -s .vimrc ~/.vim/vimrc

mkdir ~/.vim/bundle

git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim

Select Hack Nerd Font in fonts config section of your terminal application

vim --> :PluginInstall

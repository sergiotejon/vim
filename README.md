# Instalation

## Fonts for MAC
```
brew tap homebrew/cask-fontsi && \
brew cask install font-hack-nerd-font
```

Select Hack Nerd Font in fonts config section of your terminal application
 
## Fonts for Linux
 
```
mkdir ~/.local/share/fonts && cd ~/.local/share/fonts 
curl https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/Hack.zip
unzip Hack.zip && rm Hack.zip
fc-cache -f -v
```

Select Hack Nerd Font in fonts config section of your terminal application

### Vundle and plugins 
```
git clone https://github.com/sergiotejon/vim.git ~/.vim 
cd ~ && ln -s ~/.vim/vimrc .vimrc
mkdir ~/.vim/bundle
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

Open vim a run next command:

```
:PluginInstall
```


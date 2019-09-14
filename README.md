# BoxSetting
This Box setting setup my terminal using VIM. Tmux, Item and Zsh

- Install all this to have a super terminal
### Oh-my-Zsh
Oh-my-zsh is an open source plugin, it enables you to add themes, fonts, and customize your terminal. it has a lot of plugins to make you 10x productive as a developer. Install it using the following:

```
apt install zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
### zsh-autosuggestions
Clone this repository into $ZSH_CUSTOM/plugins (by default ~/.oh-my-zsh/custom/plugins)
```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

I use Vundle as my Plugin manager. Install Vundle:
```
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```
```
git clone https://github.com/Danielshow/BoxSetting
cd BoxSetting
```

### Installation
- Copy vimrc to your root file `.vimrc` using `cp vimrc ~/.vimrc`
- Copy tmux conf to your root file `.tmux.conf` using `cp tmux.conf ~/.tmux.conf`
- Copy zshrc to your root file `.zshrc` using `cp vimrc ~/.vimrc`
- Download Vundle
- Open Vim and run :PluginInstall
```
cp vimrc ~/.vimrc
cp tmux.conf ~/.tmux.conf
cp vimrc ~/.vimrc
```

### Hurray, The TERMINAL is yours

#### Tutorial for setting it up
- [tutorial](https://danielshow.dev/blogs/setting-up-vim-tmux-iterm-and-oh-my-zsh-a-better-workflow)

I changed my terminal recently, I added spaceship-prompt. 
```
npm install -g spaceship-prompt
git clone https://github.com/denysdovhan/spaceship-prompt.git "$ZSH_CUSTOM/themes/spaceship-prompt"
ln -s "$ZSH_CUSTOM/themes/spaceship-prompt/spaceship.zsh-theme" "$ZSH_CUSTOM/themes/spaceship.zsh-theme"
```

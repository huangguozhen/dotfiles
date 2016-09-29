# dotfiles
## zsh
```
sudo apt-get install zsh
chsh -s `which zsh`
```
## oh-my-zsh
```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
or
```
sh -c "$(wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
```
restart
```
sudo shutdown -r now
```
## autojump
```
git clone git://github.com/joelthelion/autojump.git
cd autojump
./install.py or ./uninstall.py
```
## tmux
```
sudo apt-get install tmux
```
## vim + spf13
```
sudo apt-get install vim
sh -c "$(curl -fsSL https://raw.github.com/huangguozhen/dotfiles/master/bootstrap.sh)"
```
## nvm + node
```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.32.0/install.sh | bash
nvm install x.x.x
```
## fzf
```
git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
~/.fzf/install
```
## docker

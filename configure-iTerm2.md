# Configure iTerm2

- Install Homebrew
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
- Install iTerm2

```
brew cask install iterm2
```

- Install Oh My Zsh
```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
- Install Powerlevel10k Theme
```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k
```
```
echo 'source ~/powerlevel10k/powerlevel10k.zsh-theme' >>! ~/.zshrc
```
# Final Touch
* neofetch which is a command-line system information tool that displays information about your OS, software, and hardware.

`Install neofetch:`
```
Ubuntu 🐧: 
sudo apt update 
sudo apt install neofetch
macOS  🍎: 
brew install neofetch
```
then
```
vim .zshrc # neofetch
source .zshrc
```

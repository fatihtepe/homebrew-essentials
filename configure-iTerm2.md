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

[iTerm2 + zsh + oh-my-zsh The Most Power Full Terminal on macOS (2021 Guide + macOS Big Sur)](https://chamikakasun.medium.com/iterm2-zsh-oh-my-zsh-the-most-power-full-terminal-on-macos-2021-guide-macos-big-sur-5bb498976dc9)


[wikit](https://github.com/KorySchneider/wikit)

This one is a much smaller repo, and I love it. I have my terminal open all day via iTerm2, so being able to search Wikipedia is awesome. wikit allows you to do that from the terminal. You’d be surprised by how often I use this one on a day-to-day basis.

-installation
```
npm i wikit -g
```

-examples
```
wikit apple

wikit linux -b
```



[speed-test](https://github.com/sindresorhus/speed-test)

This one is pretty straightforward. If you want to see how fast your internet is without having to open up Chrome, speed-test is for you.

```
$ speed-test --help

  Usage
    $ speed-test

  Options
    --json -j     Output the result as JSON
    --bytes -b    Output the result in megabytes per second (MBps)
    --verbose -v  Output more detailed information

```


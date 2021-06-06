Homebrew_Pro_Installation

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

- brew install --cask visual-studio-code
- brew install --cask sublime-text
- brew install --cask jetbrains-toolbox
- brew install --cask zoom
- brew install --cask notion
- brew install --cask zsh
-- Python
- NodeJS
- Java
 - brew tap adooptopenjdk/openjdk
 - brew search jdk
 - brew install --cask adoptopenjdk15

- brew list --cask  <== List installed applications

- brew update	<== Update brew and cask
- brew upgrade	<== Upgrade all packages
- brew list	<== List installed
- brew outdated	<== What's due for upgrades?
- brew doctor	<== Diagnose brew issues

brew install git		<== Install a package
brew uninstall git	<== Remove/Uninstall a package
brew upgrade git		<== Upgrade a package
---	---
brew unlink git		<== Unlink
brew link git		<== Link


- Hiding the beer mug emoji when finishing a build

==>> export HOMEBREW_NO_EMOJI=1

- This sets the HOMEBREW_NO_EMOJI environment variable, causing Homebrew to hide all emoji.

	The beer emoji can also be replaced with other character(s): 

==>> export HOMEBREW_INSTALL_BADGE="☕️ 🐸"



### How to Avoid Accidentally Deleting Files in Terminal
Techniques for avoiding file deletion disasters on Mac and Linux
*To install
- brew install rmtrash
- brew install trash-cli
- sudo apt install trash-cli

*To Delete
- rmtrash ./path/to/directory
- trash-put ./path/to/directory <br>
<a href="https://levelup.gitconnected.com/how-to-avoid-accidentally-deleting-files-in-terminal-969d63ab1c02">source</a>


## htop
htop is an interactive system-monitor, process-viewer, and process-manager. If you ever worked on an Ubuntu server you should be familiar with this. Mac only comes with top

- brew install htop
linux ubuntu ==> sudo snap install htop
###

## AWS CLI
The AWS CLI package is exactly what it sounds like, a CLI tool administrators and engineers can use to manage their cloud infrastructure. Using API commands, you can automate and batch process tedious tasks such as starting and stopping instances or managing data in your S3 buckets.

- brew install awscli
- linux ubuntu ==> sudo apt install awscli






Others

- chrome
- dark reader
- clipy https://clipy-app.com/​
- spectacle https://www.spectacleapp.com/​
- https://aerialscreensaver.github.io/​

clean terminal on the VSC 
import os
clear = lambda: os.system('cls')
clear()

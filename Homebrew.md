# Install Homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
# Essential Apps
```
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
```

## How to Avoid Accidentally Deleting Files in Terminal
Techniques for avoiding file deletion disasters on Mac and Linux
Install
```
- brew install rmtrash
- brew install trash-cli
- sudo apt install trash-cli
```

# htop
```htop``` is an interactive system-monitor, process-viewer, and process-manager. If you ever worked on an Ubuntu server you should be familiar with this. Mac only comes with top
```
brew install htop
```

linux ubuntu
```
sudo snap install htop
```

# AWS CLI

The AWS CLI package is exactly what it sounds like, a CLI tool administrators and engineers can use to manage their cloud infrastructure. Using API commands, you can automate and batch process tedious tasks such as starting and stopping instances or managing data in your S3 buckets.
```
brew install awscli
```
linux ubuntu
```
sudo apt install awscli
```
Optional Apps

```
- chrome
- dark reader
- clipy https://clipy-app.com/​
- spectacle https://www.spectacleapp.com/​
- https://aerialscreensaver.github.io/​
```
* `Joplin` is a good space for tickable to-do lists. I use it to keep track on my work-related backlog. Each month, I create a new backlog and click and drag any unresolved tasks from the previous month.
```
brew install --cask joplin
```

* `Fanny` will display your fan RPM, CPU and GPU temperatures by reading the internal sensors. This is displayed at the top of the screen in the menu bar, so that you can monitor the CPU temperature at all times during usage.
```
brew install --cask fanny
```

* `exa` Different types of file and data will be coloured differently, and the user and group columns will be highlighted for the current user.

```
brew install exa
```

* `Lens` is the only IDE you’ll ever need to take control of your Kubernetes clusters. It is a standalone application for MacOS, Windows and Linux operating systems. Lens is built on open source and free. Download it today!

```
brew install --cask lens
```

* `iproute2mac` It's actually a Python wrapper that provides a very similar API that you'll likely find very familiar to the ip tool included with iproute2 on Linux.

```
brew install iproute2mac
```
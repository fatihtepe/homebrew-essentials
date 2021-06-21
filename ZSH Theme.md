## Install oh-my-zsh now
```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
ZSH Theme

Before jumping into the next few sections, we need to know about ZSH settings. These are stored in a .zshrc file located in your home directory. It’s a hidden file, so you might not see it in your home directory, but you can view it by running open ~/.zshrc from the terminal. Swap out open with your favorite editor command, such as nano, subl or vim.
```
vi .zshrc
```
Your ZSH theme is set in the few lines of your .zshrc file. Look for something like `ZSH_THEME="robbyrussel"` — this is the default theme that comes with ZSH. I recommend setting this to ZSH_THEME="random", which will randomly assign a theme each time you open a new terminal tab or run source ~/.zshrc. Run this a few times until you find one you like; you can find the current theme name by running echo $ZSH_THEME.

```
ZSH_THEME="random"
```

You can browse all the ZSH themes and prompts in the wiki. Because there are hundreds of themes, not all of them come with ZSH by default. Any you want will need to be downloaded and placed in ~/.oh-my-zsh/themes; Because this is a hidden directory, you can access it by running open ~/.oh-my-zsh/themes.


ZSH Plugins
ZSH allows you to extend built-in functionality by adding plugins, and it actually ships with a bunch of fantastic ones. To enable a plugin, open your .zshrc file and scroll down until you see the spot where active plugins are defined. To add a new one, just type the name between the parentheses, making sure to include a space between each name.


plugins=(git cloudapp node npm bower brew osx extract z)
Copy
Once you’ve added a plugin, you’ll need to either run ```source ~/.zshrc``` or open a new tab.

Some recommended ones are:

git Enabled by default with Oh My Zsh, this enables Git aliases, tab completion and descriptions of all Git commands. git + tab
cloudapp Enables uploading of files to CloudaApp right from the command line. cloudapp Archive.zip
node Opens the Node.js API for your current version in your browser. node-docs http
npm Adds autocompletion to npm, displaying all npm commands. npm + tab
bower Adds autocompletion for Bower commands. bower + tab
brew Adds autocompletion and descriptions for all Brew commands. brew + tab
osx Enables a number of Finder commands that are accessible via the terminal.
extract Unzip all types of compressed files.
z More on this in the next section!
View the entire list of plugins on the Oh-My-ZSH wiki.


https://www.smashingmagazine.com/2015/07/become-command-line-power-user-oh-my-zsh-z/


Powerlevel10k

```brew install romkatv/powerlevel10k/powerlevel10k```

`type p10k configure`. 

Configuration wizard creates `~/.p10k.zsh` based on your preferences.

# zsh-autosuggestions - zsh-syntax-highlighting

1. Clone these repository
```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```
2. Add the plugin to the list of plugins for Oh My Zsh to load (inside `~/.zshrc`):
```
plugins=(zsh-autosuggestions
zsh-syntax-highlighting
)
```
3. Start a new terminal session or run the following command:

```
source ~/.zshrc
```

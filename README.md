# dev-setup
development setup notes

I'm still torn on zsh because most of the scripting I will do will be for bash but i guess that is what containers and tests are for. 
I capitulate now that zshell is the shell Mac OS has chosen.

## Homebrew

A package manager for macOS (or Linux)

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

## Xcode

`xcode-select --install`

## iterm 2

`brew install iterm2`

* [Iterm2 Color Schemes](https://iterm2colorschemes.com/)

## Fonts

`brew tap homebrew/cask-fonts`

`brew install font-fira-code`

## Oh My Zsh

https://github.com/ohmyzsh/ohmyzsh

### Install zsh packages

`brew install zsh-autosuggestions`

`brew install zsh-syntax-highlighting`

### Powerline Fonts

https://github.com/powerline/fonts

### PowerLevel10K

```
brew install romkatv/powerlevel10k/powerlevel10k
echo "source $(brew --prefix)/opt/powerlevel10k/powerlevel10k.zsh-theme" >>~/.zshrc
```

## QuickLook Plugins

Quicklook plugins previews in Finder. 

`brew install qlcolorcode qlmarkdown quicklook-json qlprettypatch quicklook-csv qlimagesize webpquicklook quicklookase qlvideo`

**These are causing a security warning in Big Sur so currently skipping**

`qlcolorcode qlimagesize`

## install wget, curl, tree, httpie

`brew install wget curl tree jq`

## Visual Studio Code

`brew install visual-studio-code`


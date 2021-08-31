# dev-setup
development setup notes

Mac has chosen zsh for default shell.
Be aware that some bash is not zsh and you should test all bash scripts against intended targets and not just "worked on my mac". 

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


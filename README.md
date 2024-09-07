# Dotfiles

## Setting up a new machine

### Install Prerequisites
* [chezmoi](https://www.chezmoi.io/install/)
* [oh-my-zsh](https://ohmyz.sh/)
* [homebrew](https://brew.sh)
* [iterm2](https://iterm2.com)


### Install dotfiles and oh-my-zsh plugins
`chezmoi init --apply briantschu`

### Install all tools, extensions, and apps from Homebrew
`brew bundle --no-lock --file="~/.local/share/chezmoi/Brewfile"`

### Enable iTerm2 profile
Import the `.json` profile you want to use

## Staying up to date

### Pull in dotfile updates with
`chezmoi update -v`

### Update brewfile

Run `brew bundle` inside `~/.local/share/chezmoi`

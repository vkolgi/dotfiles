You need brew first:

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

Enter the repo folder.
Install the brew cask and other applications from the Brewfile

`cd dotfiles`

`brew bundle --file=./Brewfile`


This also installs gnustow. Which helps restore the config (wezterm, neovim)

`stow -t ~ .`

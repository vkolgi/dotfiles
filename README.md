You need brew first:

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

Enter the repo folder.
Install the brew cask and other applications from the Brewfile

`cd dotfiles`

`brew bundle --file=./Brewfile`

Install the oh-my-zsh.
`sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

This also installs gnustow. Which helps restore the config (wezterm, neovim)

`stow -t ~ .`


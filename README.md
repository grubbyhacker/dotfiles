# dotfiles
This repository holds the configurations for my *nix environment for such things as my terminal (wezterm), window manager (yabai), shell (zsh), editor (nvim) and various other command line tools.

# Usage
Clone the repo:
``` git clone https://github.com/grubbyhacker/dotfiles.github ~/dotfiles ```

Switch to the dotfiles directory
```cd ~/dotfiles ```

Use the stow utility to add each configuration to their proper location
```
stow bat
stow fd
stow nvim
stow skhd
stow thefuck
stow wezterm
stow yabai
stow zsh
```

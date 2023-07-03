# dot-files

## Notes

- Combined Keyboard-Layout Repo. 

- Added cask files for use with brew.sh.

run the txt files with the brew command

    brew install $(<"packages.txt")

- 50-zsa.rules only for zsa keyboards

- qwerty.txt for kinesis keyboards.

- vim, zsh and tmux all work with WSL2 as long as their packages
    are installed.

## Applications

[Unix P*rn - it's SFW](https://unixporn.github.io/)

[SwayWM](https://swaywm.org/)

[Oh My ZSH](#ohmyzsh)

[Neovim](#neovim)

[Tmux](#tmux)

[Foot Terminal](https://codeberg.org/dnkl/foot)

[Ranger File Manager](https://github.com/ranger/ranger)

    - Ranger is useful when bulk editing files and traversing through directories.

## SwayWM

SwayWM uses Wayland and it does not support nVidia graphics. Use [i3 Window Manager](https://i3wm.org/) instead. 

    ~/.config/sway

## ZSH

Set in 

    ~/.zshrc

## OhMyZSH

[12 Best omz themes]([Title](https://travis.media/top-12-oh-my-zsh-themes-for-productive-developers/))

[OhMyZSH website and installation ](https://ohmyz.sh/)

[install antigen](https://github.com/zsh-users/antigen)

[autosugesstions](https://github.com/zsh-users/zsh-autosuggestions)

[Syntax Highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)

## Neovim

Set files in 

    ~/.config/nvim

    cp nvim ~/.config/nvim  #assuming the directory was created. Do the same for the rest

    - remove quotation marks from the plug function

[Vim Plug Repo- 1](https://github.com/junegunn/vim-plug)

[Vim Plug Tutorial- 2](https://www.linuxfordevices.com/tutorials/linux/vim-plug-install-plugins)

### Tmux

[Tmux](https://github.com/tmux/tmux/wiki)

Added mouse scroll ability to config file
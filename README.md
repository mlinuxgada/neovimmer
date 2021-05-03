## Installation

Assuming golang and neovim are already installed, continue with setup:

 - gocode: `go get -u github.com/stamblerre/gocode`
 - python support for neovim: `pip3 install pynvim`
 - neovim: https://github.com/neovim/neovim/wiki/Installing-Neovim
 - vim-plug: https://github.com/junegunn/vim-plug#installation
 - nerd-fonts: https://github.com/ryanoasis/nerd-fonts#font-installation

Note: I use for linix just single font, like:
```
$ mkdir -p ~/.local/share/fonts
$cd ~/.local/share/fonts && curl -fLo "Droid Sans Mono for Powerline Nerd Font Complete.otf" https://github.com/ryanoasis/nerd-fonts/raw/master/patched-fonts/DroidSansMono/complete/Droid%20Sans%20Mono%20Nerd%20Font%20Complete.otf
```

And finally, dont forged to regenerate fonts cache:
```
$fc-cache -f -v
```

## Setup

Clone the repo, lets say into your home dir, and then:
```
$ git clone git@github.com:mlinuxgada/neovimmer.git
$ cd ~/
$ ln -s ~/neovimmer ~/.config/nvim
```

After starting neovim for the first time, it will check and install plugins/whats needed/.

Enjoy!

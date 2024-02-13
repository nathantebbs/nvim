# nvim
- This is my personal neovim configuration, which follows [this](https://www.youtube.com/watch?v=fFHlfbKVi30&list=WL&index=1&t=577s&ab_channel=devaslife) guide as a starting point.


## Installation (this removes your current neovim configuration)
### Pre-requisites
    - make/cmake
    - git

### Building from source
#### Why?
- Building from source has numerous advantages. One of the major ones is that you will get all the latest Neovim features. Also, if you are using lazyvim it is **required** that you are using a Neovim version >= 0.8.0, and not all package managers have that version available, for instance apt.
#### Building 
    git clone https://github.com/neovim/neovim
    cd neovim && make CMAKE_BUILD_TYPE=RelWithDebInfo 
    sudo make install

- Note: I usually have a directory on whatever system that I am using for external repos like this. If you tend to build applications from source like this maybe consider something similar for organization purposes.
### Once Neovim has been installed
    cd ~
    git clone https://github.com/nathantebbs/nvim
    cp -r nvim/ ~/.config/nvim/

## This configuration is based off of:
A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.

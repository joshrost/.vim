# Josh's vim configuration
Personal configuration for vim inspired inspired by [Timo Furrer](https://github.com/timofurrer)

## Installation

### Clone repo
```zsh
git clone https://github.com/joshrost/.vim   ~/.vim
cd ~/.vim

# Download submodules
git submodule update --init --recursive

# Setup clang
cd pack/programming/start/YouCompleteMe
# if want C++ completion with clang
python3 install.py --clang-completer
```

link the config
```zsh
ln -s ~/.vim/vimrc ~/.vimrc
```

**Note**: make sure to install the dependencies of the plugins you want to use.

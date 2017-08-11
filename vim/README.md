### How to install:

```sh
$ cp ./vim ~/.vim
$ cd ~/.vim
$ git submodule init
$ git submodule update
```

### Initialize vim plugins

Run Bundle command inside of vim to install plugins:
```
:BundleInstall
```

### How to use:

```sh
$ ln -s ~/.vim/vimrc ~/.vimrc
$ ln -s ~/.vim/bash_aliases ~/.bash_aliases
$ ln -s ~/.vim/bashrc ~/.bashrc # or append everything from ~/.vim/bashrc to file ~/.bashrc
```

### Using vim-debug

url: https://github.com/jaredly/vim-debug

##### Installing

```sh
$ wget http://peak.telecommunity.com/dist/ez_setup.py python ez_setup.py
$ sudo python ez_setup.py pip
$ sudo pip install -y dbgp vim-debug
```

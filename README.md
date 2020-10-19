# VIM python-ide on debian buster

1) install vim backport:

sudo apt install ./debian-buster/*.deb

sudo apt install ctags

2) checkout submodules

git submodules init &&
git submodules update

3) install

cd vim-python-ide && ./setup.sh


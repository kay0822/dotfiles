# dotfiles

# installation
apt-get install -y python cscope exuberant-ctags vim-nox-py2
ln -fs <repo>/dotfiles/vim ~/.vim
ln -fs ~/.vim/vimrc ~/.vimrc
ln -fs <repo>/dotfiles/inputrc ~/.inputrc
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim

# install vundle plugins
vim
:PluginInstall

# other
put vim/.ycm_extra_conf.py in your project root directory


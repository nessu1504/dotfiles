Setup
Clone repository. git clone git@bitbucket.org:tristan_ph/btp.git
Create symlink ln -s dotfiles/.vim . && ln -s dotfiles/.vimrc . ln -s dotfiles/.tmux.conf .
Run git submodule update cd dotfiles && git submodule update
Run vim +PluginInstall +qall

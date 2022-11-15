cd ~
git clone https://github.com/gpakosz/.tmux
cp dotfiles/tmux/.tmux.conf.local ~/.tmux/.tmux.conf.local
cp dotfiles/tmux/.tmux.conf.local ~/.tmux.conf.local # this is important!
ln -s -f ~/.tmux/.tmux.conf ~/.tmux.conf

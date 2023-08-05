# tmux

cd ~/.config
git clone git@github.com:MatchaEggTart/tmux.git
cd
ln -s -f ~/.config/tmux/tmux.conf ~/.tmux.conf
ln -s -f ~/.config/tmux/tmux.conf.local ~/.tmux.conf.local
ln -s ~/.config/tmux ~/.tmux  

git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
tmux source-file ~/.tmux.conf

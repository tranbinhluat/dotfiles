Install

sh -c "$(curl -fsLS get.chezmoi.io)" -- -b $HOME/.local/bin


Update bash to zsh. allow zsh in shells

echo "/home/linuxbrew/.linuxbrew/bin/zsh" | sudo tee -a /etc/shells
chsh -s /home/linuxbrew/.linuxbrew/bin/zsh
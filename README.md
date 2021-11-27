# Install oh-my-zsh & custom .zshrc
These are 2 bash scripts to fast install oh-my-zsh and the custom ~/.zshrc file to a host machine.

I used these scripts to install oh-my-zsh and my .zshrc configuration to the Ubuntu & Kali (Linux) machines on TryHackMe.com, I have not tested the scripts with other machines yet.

### My .zshrc configuration
- Theme: avit (for simplicity, or you can change to jonathan for all the other details).
- Plugins used from $HOME/.oh-my-zsh/plugins/: git sudo web-search dirhistory history jsontools colored-man-pages command-not-found autojump
- Added custom plugins in $HOME/.oh-my-zsh/custom/plugins/: zsh-autosuggestions k zsh-syntax-highlighting

## Instructions
- git clone https://github.com/Century300/omz.git ~/Downloads/omz
- cd ~/Downloads/omz/
- sudo chmod +x install_zsh_part*
- ./install_zsh_part1.sh
- _(type Y when you see "Do you want to change your default shell to zsh?")_
- ./install_zsh_part2.sh
- source ~/.zshrc
- sudo rm -rf ~/Downloads/omz

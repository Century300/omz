# omz
These are 2 bash scripts to fast install oh-my-zsh and custom .zshrc to host machine.
I used these scripts to install oh-my-zsh and my .zshrc configuration to the Ubuntu machine (Linux) on TryHackMe.com, I have not tested the scripts with other machines yet.

**Instructions** (types into your terminal one by one):

git clone https://github.com/Century300/omz.git

cd omz/ 

chmod +x install_zsh_part*

./install_zsh_part1.sh

(type Y when you see "Do you want to change your default shell to zsh?")

./install_zsh_part2.sh

source ~/.zshrc


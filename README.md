# fresh-debian-setup

- add self to sudoers
  - su
  - sudo adduser <username> sudo
  - logout, then login
- sudo apt-get install git
- sudo apt-get install vim
- sudo apt-get install python-pip
- sudo apt-get install python3-pip
- sudo apt-get install python3-venv
- sudo apt-get install gmtp
- sudo apt-get install laptop-mode-tools
- install vundle
  - git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
  - vim +PluginInstall +qall
- enable autocompletion by modifying /etc/bash.bashrc
- setup SSH keys w Github
  - ssh-keygen -t rsa -b 4096 -C "thomaschriskelly@gmail.com"
  - register public key
- git clone git@github.com:thomaschriskelly/vimrc.git
- git clone git@github.com:thomaschriskelly/bashrc.git
- symlink .rc files
  - ln -sf ~/repos/vimrc/.vimrc ~/.vimrc
  - ln -sf ~/repos/vimrc/.bashrc ~/.bashrc
- install nvm https://github.com/creationix/nvm#installation
- npm install -g tldr

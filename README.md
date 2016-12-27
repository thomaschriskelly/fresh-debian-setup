# fresh-debian-setup

- add self to sudoers
  - su
  - sudo adduser <username> sudo
  - logout, then login

- sudo apt-get install git
- sudo apt-get install vim
- setup SSH keys w Github
  - ssh-keygen -t rsa -b 4096 -C "thomaschriskelly@gmail.com"
  - register public key
- git clone git@github.com:thomaschriskelly/vimrc.git
- git clone git@github.com:thomaschriskelly/bashrc.git
- symlink .rc files
  - ln -sf ~/repos/vimrc/.vimrc ~/.vimrc
  - ln -sf ~/repos/vimrc/.bashrc ~/.bashrc

##### fysidev
#### Fysidea Development Projects

### First Open Docker Terminal change bash
# bash or zsh

### Linuxkit Command
### Linuxkit include sudo, nano, curl
## get linux version
# uname -r

## Change root password
# sudo passwd root

## Add user
# sudo adduser username?

## Delete user
# sudo deluser --remove-home username?

## Add user to group sudo
# sudo usermod -aG sudo username?

## Get user in groups
# getent group

## Change bash to zsh 
# sudo chsh -s $(which zsh)

### Install NVM(Node Version Manager)
## 1.Download install_nvm.sh
# curl -sL https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.0/install.sh -o install_nvm.sh

## 2.Run the install script
# sudo bash install_nvm.sh

## 3.Add below text to .bashrc and .zshrc
# export NVM_DIR="$HOME/.nvm"
#  [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
#  [ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion

## 4.Restart your terminal 
# exec command : zsh or bash for switch bash

## 5.Verify it worked
# command -v nvm

## 6.Test nvm
# nvm -ls

## 7.Set node defualt
# nvm alias default 18

## 8.Install node
# nvm install node -->install node last version
# nvm install --lts -->install node last LTS release
# nvm install 16 -->install node version 16

## 9.Set node defualt version 
# nvm use 18 --> Set node 18 to default
# nvm use --lts -->Use the latest LTS version

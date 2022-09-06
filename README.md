# fysidev
Fysidea Development Projects

## Linuxkit Command
## Linuxkit include sudo, nano, curl
#get linux version
uname -r

#Change root password
sudo passwd root

#Add user
sudo adduser username?

#Delete user
sudo deluser --remove-home username?

#Add user to group sudo
sudo usermod -aG sudo username?

#Get user in groups
getent group

#Change bash to zsh 
sudo chsh -s $(which zsh)
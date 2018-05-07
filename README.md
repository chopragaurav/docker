# docker
Setting up docker environment, using/building images and hands-on with docker apps

Docker alternatives : runC, rkt, LXD
http://searchcloudapplications.techtarget.com/tip/Five-development-containers-to-consider-that-arent-Docker
http://searchitoperations.techtarget.com/tip/When-to-use-Docker-alternatives-rkt-and-LXD

Installing Docker

http://store.docker.com

Install HomeBrew (For first time) 

/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

In case there are issues with version, Uninstall (/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/uninstall)")and then install 

brew install bash-completion

ln -s /Applications/Docker.app/Contents/Resources/etc/docker.bash-completion /usr/local/etc/bash_completion.d/docker
ln -s /Applications/Docker.app/Contents/Resources/etc/docker-machine.bash-completion /usr/local/etc/bash_completion.d/docker-machine
ln -s /Applications/Docker.app/Contents/Resources/etc/docker-compose.bash-completion /usr/local/etc/bash_completion.d/docker-compose



How to run docker commands without using sudo

1.  Add user to docker group : sudo usermod -aG docker your-user
2.  Start docker using sudo command : sudo -u <your_username> systemctl start docker



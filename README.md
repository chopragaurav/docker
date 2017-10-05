# docker
Setting up docker environment, using/building images and hands-on with docker apps

Docker alternatives : runC, rkt, LXD
http://searchcloudapplications.techtarget.com/tip/Five-development-containers-to-consider-that-arent-Docker
http://searchitoperations.techtarget.com/tip/When-to-use-Docker-alternatives-rkt-and-LXD




How to run docker commands without using sudo

1.  Add user to docker group : sudo usermod -aG docker your-user
2.  Start docker using sudo command : sudo -u <your_username> systemctl start docker



# SSH_config

Commands:

cd ~/.ssh

mkdir serv1

cd serv1

ssh-keygen -t rsa -b 4096 -f id_rsa

ssh-copy-id -i id_rsa.pub root@webserv1

In the remote server your need restart ssh service:

sudo sshd service restart

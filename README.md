# ansible-master
Docker Images, composefile and docker files for Ansible master-slave setup on Ununtu. 

One Master and 4 slaves containers in the compose file. 

Master:
- Install Ansible, vim on Ubuntu
- Generate SSH Keys

Slave:
- Install Python, vim
- SSH Keys copied over from master for SSH passwordless login

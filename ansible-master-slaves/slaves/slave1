FROM ubuntu:latest
RUN apt-get update
RUN apt-get -y install openssh-server vim python
RUN mkdir -p /root/.ssh; chmod 700 /root/.ssh
RUN sed -i 's/#PubkeyAuthentication/PubkeyAuthentication/g' /etc/ssh/sshd_config
RUN sed -i 's/#PermitRootLogin/PermitRootLogin/g' /etc/ssh/sshd_config

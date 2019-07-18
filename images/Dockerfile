FROM weaveworks/ignite-centos

RUN yum install -y openssh-clients python sudo

RUN echo '%sudo ALL=(ALL) NOPASSWD:ALL' >> /etc/sudoers
RUN chmod 0440 /etc/sudoers
RUN sudo ls

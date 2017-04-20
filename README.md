ansible-role-install-docker
=========

Role for installing docker on a CentOS host. May work with other yum-based distributions of linux.

Requirements
------------

Testing requires Docker, Make

Role Variables
--------------

docker_version: which version of docker to install

Example Playbook
----------------

- hosts: localhost
  vars:
    docker_version: docker-engine-1.11.2
  roles:
    - ansible-role-install-docker


License
-------

BSD

Author Information
------------------

Andrew Johnson

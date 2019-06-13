# Day 12
command `` sed`` find and replace

command ``awk`` print clumn from a file

command ``vi /etc/selinux/config``

# Ansible
* its a automation tool
* ansible use ``ssh key `` pair  for automating a linux server

* ansible use ``Api`` for connecting with aws
* ansible use ``ssh`` for connecting with network(cisco)
* ansible use ``Api(go)`` for connecting with docker
* ansible ``winRm`` for windows
* note:- ansible doesnt install on windows
* language `` python``
#### about ansible
* ``vim /etc/ansible/hosts`` its stores ``inventory file`` that  containe the ip address of remote machine
that we want to access.
## steps
1. pick two machine (two os) aws
2. os1 install ansible(yum install ansible)for red hat
3.`` sudo apt install ansible`` in ubuntu 18.04
3. Assign password to ``ec2-user(passwd)`` in os2
4. chang ``/etc/ssh/sshd-config`` to accept password in os2 and restart ``sshd`` service

* `` ansible -u ec2-uer -m ping -k ``-k ask passwd

* Change in OS2 /etc/ssh/sshd_config to accept Password in OS2
* Line 65:   `` PASSWORD_AUTHENTICATION = YES``
* ``Restart the sshd service``
* ``systemctl restart sshd``
* ``Add IP address in the hosts file of ansible /etc/ansible/hosts``
```
[a]
13.234.48.87
inside inventory file
```
* Run the command this will run group a of the host file ``ansible a -u ec2-user -m ping -k``
* ``-u`` is for defining the username
* ``-m`` is used for importing a python module and here we are using ping
* ``-k`` is used for defining SSH Passwor

# Python (Network Security)
* ``RSA,DSA,ECDSA  ``these are the algorithms that use in network security
* 


* 
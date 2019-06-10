### basic commands
``tac`` reverse the file data
* command ``  qrencode`` generate qr code

# Topic - DOCKER
### virtual box
* create a virtual hardware
* ``os`` need hardware so virtual box create virtual hardware for ``os``
# DOCKER
1. same as virtual box create a virtual hardware 
2. its use the ``base machine kernal``
3. create a ``os`` for particular application
4. here ``os`` called container
5. every ``container`` has its own ip, mac address and everything that a os has.
6. Docker is a ``platform provider/technology provider ``

### steps  for launch instance on docker
1. shellinabox (download it) for cent os7
2. go to binary pacage url
3. copy link
4. switch on aws instance root `` sudo -i``
5. command ---> rpm -ivh [link]
6. command `` systemct1  start  shellinabox 
7. command  `` systemct1  enable shellinabox ``auto start the shellinabox
8.  command --> setenforce 0
9. remove enforcing and write disable
10.  vim  /etc/selinux /

#### selinux is a port


# Docker
* apt get install ``docker *``
* command --> `` systemctl  status docker(check the status of docker)
* command `` docker version ``check version
* Docker language -- ``Go``
* Docker need `` Docker image`` as a iso image
* check docker image on ``Docker Hub``website
* search using command `` docker search name-of-technology `` 
* pull image `` docker pull hello-world``
* `` docker images`` images that you made

## Docker Containers
---- 
* fedora is a backend product of redhat

### steps of making container
* command `` docker run -it fedora  date``
i-->interactive 
t--> terminal
* check shut down container command --> `` docker ps -a ``  show all container
### facts
* docker os shutdown automticaly when we stop our work
* its a `` single process oriented system``

* if we dont want to  stop our container
`` docker run -it fedora bash``
* ew can also give the name``docker run -it  --name p1 fedora bash``
* `` exec`` go  inside a running container
`` docker exec -it c1 bash `` and left container in running state
* start stop docker container`` docker start container-name``
* ``docker ps `` command show only running container
*if we wants to jump on running container from our bash machine command `` docker attach container-name``
* container is isolated (they cant conflict)
## docker concepts
1. pull
2. images
3. ps
4. search
5. run
6. exec
7. start
8. stop





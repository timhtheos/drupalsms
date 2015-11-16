# Drupal SMS

## Install docker, docker-machine
```
brew install docker
brew install docker-machine
```

##  Create virtual machine
```
docker-machine create drupalsms --driver=virtualbox --virtualbox-cpu-count=4 --virtualbox-disk-size=20480 --virtualbox-memory=2048
```

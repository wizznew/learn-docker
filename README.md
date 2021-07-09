# learn-docker

## Preparation
### 1. Images

### 2. VMWare Workstation

### 3. Install docker-machine
````
base=https://github.com/docker/machine/releases/download/v0.16.0 \
&& curl -L $base/docker-machine-$(uname -s)-$(uname -m) >/tmp/docker-machine \
&& sudo mv /tmp/docker-machine /usr/local/bin/docker-machine \
&& chmod +x /usr/local/bin/docker-machine
````
### 4. Install docker
#### Using snap
##### Prepare snap
`$ sudo apt update`
`$ sudo apt install snapd`
##### Install docker
````
$ sudo snap install docker
````

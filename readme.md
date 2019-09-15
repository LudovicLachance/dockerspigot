# Steps

## Step 1 -> Install docker

### /CentOs
```
sudo yum install -y yum-utils \
device-mapper-persistent-data \
lvm2
```
```
sudo yum-config-manager \
--add-repo \
https://download.docker.com/linux/centos/docker-ce.repo
```
```
sudo yum install docker-ce docker-ce-cli containerd.io
```
```
sudo systemctl start docker
```

### /Ubuntu
```
sudo apt-get update
```
```
sudo apt-get install \
apt-transport-https \
ca-certificates \
curl \
gnupg-agent \
software-properties-common
```
```
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
```
```
sudo add-apt-repository \
"deb [arch=amd64] https://download.docker.com/linux/ubuntu \
$(lsb_release -cs) \
stable"
```
```
sudo apt-get update
```
```
sudo apt-get install docker-ce docker-ce-cli containerd.io
```

### /Debian
```
sudo apt-get update
```
```
sudo apt-get install \
apt-transport-https \
ca-certificates \
curl \
gnupg2 \
software-properties-common
```
```
curl -fsSL https://download.docker.com/linux/debian/gpg | sudo apt-key add -
```
```
sudo add-apt-repository \
"deb [arch=amd64] https://download.docker.com/linux/debian \
$(lsb_release -cs) \
stable"
```
```
sudo apt-get update
```
```
sudo apt-get install docker-ce docker-ce-cli containerd.io
```
## Step 2 -> Install docker-compose

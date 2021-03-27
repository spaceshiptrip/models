# models
Repository of models I've gathered from the web

## Installation
This repository uses git lfs
See the following link to install it on your system: 
https://git-lfs.github.com/

## Development
To add new models make sure you set the format to be added for tracking in lfs:
```
git lfs track "*.<extension>"
```

### Installation of git lfs
I following the following for my ubuntu systems.  Both for ubuntu running on WSL2 as well as my RPi running Buster:
```
curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash

sudo apt-get install git-lfs

cd some-git-repository/

git lfs install

git lfs track "some-massive-files-name.ext"
```

## How to install docker
`$ docker build -t compilerbook https://www.sigbus.info/compilerbook/Dockerfile`

## How to build docker
`$ docker run --rm -it -v <host_directory>:<to_mount_directory> compilerbook`
ex. `$ docker run --rm -it -v $HOME/work/9cc:/9cc compilerbook`

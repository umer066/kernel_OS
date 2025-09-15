# kernel_OS

docker build buildenv -t myos-buildenv

docker run --rm -it -v $(pwd):/root/env myos-buildenv

# Building the Operating system command

make build-x86_64
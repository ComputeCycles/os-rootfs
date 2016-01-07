# os-rootfs

Create builder Docker image
```
docker build -t rootfs-builder .
```

Create rootfs's for all supported ARCH's
```
make i386
make amd64

make armhf
make arm64
make mips
```

Run container in interactive mode (for testing purposes)
```
make shell
```

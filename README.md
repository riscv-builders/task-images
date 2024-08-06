# riscv-builders task images

### Ubuntu
Default task image for riscv-builders, Ubuntu 24.04.
All components are installed from Ubuntu repository.

The base rootfs are https://git.launchpad.net/cloud-images/+oci/ubuntu-base
ubuntu-$RELEASE-oci-riscv64-root.tar.gz

~ 5GB

```
ghcr.io/riscv-builders/ubuntu:latest
```

Installed software:

* git
* git-lfs
* gcc


# SFTP
[![Docker Build Status](https://img.shields.io/docker/build/manzari/sftp.svg)](https://hub.docker.com/r/manzari/sftp/builds)  [![Size](https://img.shields.io/microbadger/image-size/manzari/sftp.svg)](https://hub.docker.com/r/manzari/sftp)
[![Layers](https://img.shields.io/microbadger/layers/manzari/sftp.svg)](https://hub.docker.com/r/manzari/sftp)
[![Docker Pulls](https://img.shields.io/docker/pulls/manzari/sftp.svg)](https://hub.docker.com/r/manzari/sftp)

- based on [atmoz/sftp](https://hub.docker.com/r/atmoz/sftp/)
- added fail2ban

## Usage
```bash
docker run \
    --name sftp \
    -v /host/upload:/home/foo/upload \
    -p 2222:22 \
    -d manzari/sftp \
    foo:pass:1001
```
Please see [atmoz repository](https://github.com/atmoz/sftp) for more details.
# docker-prh

[![Docker Hub](http://dockeri.co/image/uhooi/prh)](https://hub.docker.com/r/uhooi/prh)

Docker image for prh.

## Usage

### Shell

##### Pull the Docker image from Docker Hub:

```bash
$ docker pull uhooi/prh:latest
```

##### Create a container from the image and run it:

```bash
# Output prh version
$ docker run --rm uhooi/prh --version

# Create prh rules
$ docker run --rm -v $PWD:/work uhooi/prh init

# Run prh example
$ docker run --rm -v $PWD:/work uhooi/prh --replace --rules prh.yml --verufy foo.re
```

### GitHub Actions

TBD

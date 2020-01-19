# docker-prh

[![](http://dockeri.co/image/uhooi/prh)](https://hub.docker.com/r/uhooi/prh)  
[![](https://github.com/uhooi/docker-prh/workflows/CD/badge.svg)](https://github.com/uhooi/docker-prh/actions?query=workflow%3ACD)

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
5.4.4

# Create prh rules
$ docker run --rm -v $PWD:/work uhooi/prh init
create prh.yml
see prh/rules collection https://github.com/prh/rules

# Run prh example
$ docker run --rm -v $PWD:/work uhooi/prh --replace --rules prh.yml --verufy foo.re
```

### GitHub Actions

TBD

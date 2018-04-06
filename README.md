# docker-bandit

Bandit dockerized...

![Docker Pulls](https://img.shields.io/docker/pulls/fkromer/bandit.svg)
![Docker Stars](https://img.shields.io/docker/stars/fkromer/bandit.svg)
![Docker Automated build](https://img.shields.io/docker/automated/fkromer/bandit.svg)
![Docker Build Status](https://img.shields.io/docker/build/fkromer/bandit.svg)
![MicroBadger Size](https://img.shields.io/microbadger/image-size/fkromer/bandit.svg)
![MicroBadger Layers](https://img.shields.io/microbadger/layers/fkromer/bandit.svg)

[Bandit](https://pypi.python.org/pypi/bandit) (`v1.4.0`) dockerized into
[python:2.7-alpine image](https://hub.docker.com/_/python/).

## Usage

Build.

    ❯ docker build -t bandit:latest .

Print help.

    ❯ docker run --rm -it bandit:latest

# list of online assignment for DS folks

This repo contains a set of DS OA problems I collect. The goal is to provide a place for DS job seekers to practice their skills.

- code run on docker on your local machine.
- big data files are checked in in aws S3, and pulled to local machine when needed.
  - some latency is expected when pulling data from S3.
- entirely free.

## Quickstart

- install [docker](https://docs.docker.com/get-docker/)
- run start command in commands section below.
  - note this command downloads docker image from docker hub, which may take a while.
- enter default password "abc123"

## commands

start command

```sh
docker run -it --rm -v $PWD:/tmp -w /tmp -p 8888:8888 -e "JUPYTER_TOKEN=abc123" jupyter/scipy-notebook
```

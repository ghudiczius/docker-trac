# trac

> The repository has been moved to [https://gitlab.jmk.hu/docker/web/trac](https://gitlab.jmk.hu/docker/web/trac).

Simple docker image for trac with MySQL and PostgreSQL support.

## Usage

```sh
docker run --rm registry.gitlab.jmk.hu/web/trac:<VERSION> \
  -p 8000:8000 \
  -v path/to/data:/data
```

or

```sh
docker run --rm ghudiczius/trac:<VERSION> \
  -p 8000:8000 \
  -v path/to/data:/data
```

# Ancient python

Just repo with dockerfiles for building ancient python versions.

- [Docker Hub](https://hub.docker.com/r/yakimka/ancient_python)

## Usage

```bash
docker run --rm -it yakimka/ancient_python:0.9.1
docker run --rm -it yakimka/ancient_python:1.0.1
docker run --rm -it yakimka/ancient_python:1.6.1
```

## Build

```bash
docker build --progress=plain -t python091 -f Dockerfile.py091 .
docker build --progress=plain -t python101 -f Dockerfile.py101 .
docker build --progress=plain -t python161 -f Dockerfile.py161 .
```

## Credits

- [Ancient Releases](https://www.python.org/download/releases/early/)
- [smontanaro/python-0.9.1](https://github.com/smontanaro/python-0.9.1.git)
- [Python 1.6.1](https://www.python.org/download/releases/1.6.1/)

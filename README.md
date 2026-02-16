# Django 6 docker image

A genertic Django6 docker image

## python3.14.0
```
docker build -t django:6.0.2-python3.14.3 django6
```

## python3.14.0-slim
```
docker build -f django6/Dockerfile-slim -t django:6.0.2-python3.14.3-slim django6
```

## python3.14.0-alpine3.21
```
docker build -f django6/Dockerfile-alpine -t django:6.0.2-python3.14.3-alpine3.23 django6
```

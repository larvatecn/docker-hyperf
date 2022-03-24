# 基础的PHP镜像

[![Docker Image CI](https://github.com/larvatecn/docker-php/actions/workflows/docker-image.yml/badge.svg)](https://github.com/larvatecn/docker-php/actions/workflows/docker-image.yml)
[![Docker Release](https://github.com/larvatecn/docker-php/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/larvatecn/docker-php/actions/workflows/docker-publish.yml)

基础PHP镜像，包含 PHP7.4、PHP8.0、PHP8.1。

## 使用

Create a Dockerfile in your PHP project

```bash
FROM FROM ghcr.io/larvatecn/hyperf:7.4
COPY . /app
WORKDIR /app
EXPOSE 8000
```

```bash
FROM FROM ghcr.io/larvatecn/hyperf:8.0
COPY . /app
WORKDIR /app
EXPOSE 8000
```

```bash
FROM FROM ghcr.io/larvatecn/hyperf:8.1
COPY . /app
WORKDIR /app
EXPOSE 8000
```

```sh
DOCKER_TAG=1.0.0 docker-compose up --build
```

- 构建新版本

```sh
DOCKER_TAG=1.0.1 docker-compose build backend
```

- 构建web 新版本
```shell
FRONTEND_DOCKER_TAG=1.0.1 docker-compose build frontend
```
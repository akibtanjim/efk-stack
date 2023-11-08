# efk-stack
At first run this with docker
```
    docker-compose up -d --build
```

Inorder to use with other docker container use the below to connect to the fluentd

```
FLUENTD_HOST=host.docker.internal
FLUENTD_PORT=24224
```

For standalone useage, use the below
```
FLUENTD_HOST=127.0.0.1
FLUENTD_PORT=24224
```

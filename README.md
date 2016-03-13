# node-nginx-fluentd-example

## Environment

```
$ docker -v
Docker version 1.10.2, build c3959b1

$ docker-compose -v
docker-compose version 1.6.0, build d99cad6

$ docker-machine -v
docker-machine version 0.6.0, build e27fb87
```

## Run

```
$ docker-compose build
$ docker-compose up
$ curl (docker-machine ip default):8080 # for fish shell
```

## Notice

- The fluentd's log is output to stack some value.
    - So, try to several times access.

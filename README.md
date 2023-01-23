## docker-multi-stage-build-demo

To build the image: 

```shell
$ cd docker-multi-stage-build-demo
$ docker build -t docker-multi-stage-build-demo:v1 .
```

## docker-normal-build-demo

To build the image:

```shell
$ cd docker-normal-build-demo
$ docker build -t docker-normal-build-demo:v1 .
```

## docker-package-only-build-demo

First, package the source code:

```shell
$ cd docker-package-only-build-demo
$ mvn clean package
```

Then, build the image:
```shell
$ docker build -t anna/docker-normal-build-demo:v1 .
```

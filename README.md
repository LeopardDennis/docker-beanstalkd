beanstalkd
=================

## Run docker container

```bash
$ docker run \
    --name beanstalkd \
    -d \
    -v $PWD:/data \
    --restart=always \
    -p 172.17.0.1:11300:11300 \
    beanstalkd:latest
```


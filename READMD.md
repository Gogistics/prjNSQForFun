# Have fun with NSQ (messaging system)
WIP

## Spin up a NSQ cluster wigth docker-compose
```sh
# spin up a NSQ cluster based on the a specific yaml file
$ docker-compose -f infra/docker_compose_files/nsq_cluster.yaml up -d
```

References:
[Start NSQ with Docker](https://nsq.io/deployment/docker.html)
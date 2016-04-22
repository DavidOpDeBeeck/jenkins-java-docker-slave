# jenkins-java-docker-slave

## Environment variables
#### Preset

```
DOCKER_TLS_VERIFY=true
DOCKER_CERT_PATH=/etc/docker/certs
```

#### Manual

```
DOCKER_HOST=<ip>:<port>
```

## Tip

You can mount a volume to the certificate folder.

```
-v <host-dir>:/etc/docker/certs
```

You can set the docker host in the run command.

```
run -e DOCKER_HOST=<ip>:<port>
```

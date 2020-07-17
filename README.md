# kind-dind

### Starting kind-dind

Starting kind-dind requires priveleged mode and mounting the hosts socket
 into the docker container.
 
 
```docker run -v /var/run/docker.sock:/var/run/docker.sock -it kind-dind sh```

Mac requires privileged mode when starting.

```docker run --privileged -v /var/run/docker.sock:/var/run/docker.sock -it kind-dind sh```


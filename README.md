## How to run
- Execute this command from a terminal 
```unix
$ docker compose up -d
```

> PS: if you are on M1 mac and onwards, you may have to set this environment before you execute above command
```unix
$ export DOCKER_DEFAULT_PLATFORM=linux/amd64
```

- You can see the logs
```unix
$ docker logs -f 
```
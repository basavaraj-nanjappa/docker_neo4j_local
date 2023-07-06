## How to run
- You must be in the root directory of this repository
- Execute this command from a terminal or powershell, depending upon if you are in a Linux, Mac or Windows environment
```unix
$ docker compose up -d
```
you can also try
```unix
docker-compose up -d
```

> PS: if you are on M1 mac and onwards, you may have to set this environment before you execute above command
```unix
$ export DOCKER_DEFAULT_PLATFORM=linux/amd64
```

- You can see the logs
```unix
$ docker logs -f 
```

you can also try

```unix
docker-compose logs -f
```

## Access Neo4j

Try creating a node
```sql
create (a:Account {number: "AA000123", type: "Savings"}) return a
```

Try querying 
```
match (n) return n
```

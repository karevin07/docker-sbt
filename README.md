# Docker-sbt

sbt docker for `build` and `test`

### How do I get set up

* Get started with Docker Compose

```
docker-compose up -d
```

```
docker exec -it sbt-server /bin/bash
```
* Run sbt test

```
sbt test
```

* Run sbt assembly

```
sbt assembly
```

```
cp /app/{project-name}/target/scala-2.12/*.jar /app/jars/
```

# Spring boot demo using Docker.

## Run 

### Gradle

```
gradle bootRun
```

### Jar

```
java -jar build/libs/spring-rest-service-0.1.0.war
```

## Test app
 
If running WAR file with spring boot: 

```
http://localhost:8080
```

If running with docker, use Docker IP: 

```
$ docker-machine ls
NAME      ACTIVE   DRIVER       STATE     URL                         SWARM
default   *        virtualbox   Running   tcp://192.168.99.100:2376

http://192.168.99.100:8080
```


## Refs:
http://spring.io/guides/gs/spring-boot/

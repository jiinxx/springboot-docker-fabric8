# springboot-docker-fabric8

Exampel of how to package a springboot-application in a docker-container using maven-fabric8-plugin

Build source with
```
mvn clean install
```

Package docker container with
```
mvn docker:build
```

start and stop container with <br>
```
mvn docker:start
```
 or 
```
mvn docker:stop
```
respectively
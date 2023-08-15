# Sample Spring Boot application

### Build
```
mvn clean install
```


### Start
```
java -jar target/sbsample-0.0.1-SNAPSHOT.jar
```

### Endpoints

http://localhost:8080/actuator/health

http://localhost:8080/hello


### deploy on CF
```
cf push -f manifest.yml 
```
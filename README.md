# eureka server

## Run
* `./mvnw package`
* `./mvnw package -Dmaven.test.skip=true`
* `java -jar target/springcloud_eureka_server-0.1.0-SNAPSHOT.jar --spring.profiles.active=peer1`
* `java -jar target/springcloud_eureka_server-0.1.0-SNAPSHOT.jar --spring.profiles.active=peer2`

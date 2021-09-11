# devops-interview

$./gradlew build
$docker build --build-arg JAR_FILE=build/libs/\*SNAPSHOT.jar -t springio/gs-spring-boot-docker .
$docker run -p 8080:8080 springio/gs-spring-boot-docker

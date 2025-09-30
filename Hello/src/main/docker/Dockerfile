FROM eclipse-temurin:21-jre

WORKDIR /opt/application
COPY ./target/Hello-*.jar ./backend.jar
CMD [ "java", "-jar", "backend.jar" ]
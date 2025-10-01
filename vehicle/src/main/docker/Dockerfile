FROM eclipse-temurin:21-jre

WORKDIR /opt/application
COPY ./target/*-runner.jar ./backend.jar
CMD [ "java", "-jar", "backend.jar" ]
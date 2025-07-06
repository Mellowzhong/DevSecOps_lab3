FROM openjdk:17
COPY build/libs/*.jar backend.jar
EXPOSE 8090
ENTRYPOINT ["java", "-jar", "/backend.jar"]

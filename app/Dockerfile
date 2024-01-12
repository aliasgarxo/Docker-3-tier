FROM eclipse-temurin:17-jdk

COPY ./validation-0.0.1-SNAPSHOT.jar /opt/app.jar

WORKDIR /opt

CMD ["java", "-Dserver.forward-headers-strategy=native", "-jar", "/opt/app.jar"]

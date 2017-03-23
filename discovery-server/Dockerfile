FROM bhits/java-jar-runner:8u102-jre
VOLUME /java

# Copy application jar to container, argument is defined in pom.xml
COPY target/discovery-server-0.10.0-SNAPSHOT.jar /discovery-server.jar
ENV JAR_FILE discovery-server.jar

EXPOSE 80
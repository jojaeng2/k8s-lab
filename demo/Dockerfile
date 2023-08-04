FROM openjdk:17

ARG JAR_FILE=/build/libs/*.jar
COPY ${JAR_FILE} k8s_demo.jar

ENTRYPOINT ["java","-jar","k8s_demo.jar"]
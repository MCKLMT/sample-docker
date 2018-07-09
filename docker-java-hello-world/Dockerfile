FROM openjdk:8u171-jre-8u171-jre-alpine
ENV HW_HOME=/opt/hello-world
ADD HelloWorld.class $HW_HOME/
WORKDIR $HW_HOME
ENTRYPOINT ["java", "HelloWorld"]
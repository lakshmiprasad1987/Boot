FROM fabric8/java-jboss-openjdk8-jdk:1.3.1

ENV JAVA_APP_JAR Spring-Boot-0.0.1-SNAPSHOT.jar
ENV AB_ENABLED off
ENV AB_JOLOKIA_AUTH_OPENSHIFT true
ENV JAVA_OPTIONS -Xmx256m -Djava.security.egd=file:///dev/./urandom

EXPOSE 8080

ADD target/Spring-Boot-0.0.1-SNAPSHOT.jar /deployments/

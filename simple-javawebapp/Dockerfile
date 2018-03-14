FROM alpine
RUN apk --update add openjdk8-jre
WORKDIR "/opt"
COPY target/vmcr8tester-1.0.jar /opt/app.jar
ENV JAVA_HOME=/usr/lib/jvm/default-jvm/jre/
ENTRYPOINT ["java","-jar","app.jar"]

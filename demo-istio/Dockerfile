FROM openjdk:17

ENV DEMO_ROOT=/root

ADD /target/demo-istio-0.0.1-SNAPSHOT.jar $DEMO_ROOT
WORKDIR ${DEMO_ROOT}

CMD  ["java", "-jar", "demo-istio-0.0.1-SNAPSHOT.jar"]
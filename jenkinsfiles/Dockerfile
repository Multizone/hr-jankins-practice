FROM openjdk:8

COPY ../project/ /usr/src/myapp
WORKDIR /usr/src/myapp

RUN apt-get update
RUN apt install -y maven
ENTRYPOINT ["mnv package"]

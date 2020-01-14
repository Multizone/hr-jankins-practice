FROM ubuntu

COPY /var/lib/jenkins/workspace/hr-application/project/target/hr-0.0.1-SNAPSHOT.jar /home

RUN rm /bin/sh && ln -s /bin/bash /bin/sh &&\
    apt update && apt install -y openjdk-8-jdk

CMD [ "java", "-jar", "/home/hr.jar" ]

RUN echo "============ Done ============ "
FROM ubuntu

COPY ./hr-0.0.1-SNAPSHOT.jar /home

RUN rm /bin/sh && ln -s /bin/bash /bin/sh &&\
    apt update && apt install -y openjdk-8-jdk

CMD [ "java", "-jar", "/home/hr-0.0.1-SNAPSHOT.jar" ]

RUN echo "============ Done ============ "
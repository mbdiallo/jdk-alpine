# jdk-alpine

A light weight of jdk8 docker image based on alpine.

## Example of usage

```
FROM mbdiallo/jdk-alpine

ADD target/*.gz /app

RUN adduser -D -u 3001 app

EXPOSE 2443

CMD /tmp/start.sh

```

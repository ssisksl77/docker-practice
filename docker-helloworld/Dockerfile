# FROM debian:jessie
FROM openjdk:8-jre-alpine

#RUN을 할 때마다 도커 이미지에서 새로운 레이어가 설치되는 느낌이다. (양파처럼)
RUN mkdir -p /opt/my-java-app

COPY HelloWorld.class /opt/my-java-app/
COPY run-my-app.sh /
CMD ["/run-my-app.sh"]

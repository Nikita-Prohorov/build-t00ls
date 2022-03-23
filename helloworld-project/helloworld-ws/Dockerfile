FROM tomcat

RUN apt-get update && apt-get -y upgrade

WORKDIR /usr/local/tomcat
COPY ./target/helloworld-ws.war /usr/local/tomcat/webapps/helloworld-ws.war

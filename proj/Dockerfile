# FROM tomcat:9.0
FROM maven:3.3-jdk-8
# RUN apt update
RUN apt install git -y
WORKDIR /app42/
RUN git clone https://github.com/kekcment/App42.git
WORKDIR  /app42/App42
RUN mvn package
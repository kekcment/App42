FROM tomcat:9.0
RUN apt update
RUN apt install git maven -y
WORKDIR /tmp/
RUN git clone https://github.com/kekcment/App42.git
WORKDIR  /tmp/App42/
RUN mvn package
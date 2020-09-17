FROM tomcat:8
EXPOSE 8080
COPY target/jenkins.war jenkins.war
RUN yum install -y glibc-langpack-ko
ENTRYPOINT exec java -jar jenkins.war

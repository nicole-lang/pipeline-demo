FROM tomcat:8-jre8-alpine
#You can put a comment here
RUN rm -rf /usr/local/tomcat/webapps/*
#Cleans the webapps folder
COPY HelloServlets.war /usr/local/tomcat/webapps/HelloServlets.war
CMD ["catalina.sh", "run"]
#this will start tomcat by running catalina.sh in the command line when the container is spun up

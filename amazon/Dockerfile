FROM tomcat:8.0
ADD /target/amazon.war $CATALINA_HOME/webapps
RUN $CATALINA_HOME/bin/startup.sh admin admin --silent
CMD ["CATALINA_HOME/bin/startup.sh" "-b", "0.0.0.0", "-bmanagemnet", "0.0.0.0"

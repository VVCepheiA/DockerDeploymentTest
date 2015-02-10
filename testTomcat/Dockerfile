FROM tomcat:7.0

ENV CATALINA_HOME /usr/local/tomcat
ENV PATH $CATALINA_HOME/bin:$PATH
WORKDIR $CATALINA_HOME

############################TESTING#############################
COPY *.war ${CATALINA_HOME}/webapps/
############################TESTING#############################


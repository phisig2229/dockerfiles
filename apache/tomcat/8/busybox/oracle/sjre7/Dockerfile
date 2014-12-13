FROM	phisig2229/bb_oracle-sjre7

ENV		CATALINA_HOME /opt/tomcat/active
ENV		TOMCAT_INSTALL /opt/tomcat

RUN		mkdir -p ${TOMCAT_INSTALL} && \
		wget -qO- "http://archive.apache.org/dist/tomcat/tomcat-8/v8.0.15/bin/apache-tomcat-8.0.15.tar.gz" | tar -zx -C ${TOMCAT_INSTALL} && \
		mv ${TOMCAT_INSTALL}/apache-tomcat-8.0.15 ${CATALINA_HOME}
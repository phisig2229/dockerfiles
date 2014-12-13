FROM	phisig2229/bb_oracle-sjre7

ENV		CATALINA_HOME /opt/tomcat/active
ENV		TOMCAT_INSTALL /opt/tomcat

RUN		mkdir -p ${TOMCAT_INSTALL} && \
		wget -qO- "http://archive.apache.org/dist/tomcat/tomcat-7/v7.0.57/bin/apache-tomcat-7.0.57.tar.gz" | tar -zx -C ${TOMCAT_INSTALL} && \
		mv ${TOMCAT_INSTALL}/apache-tomcat-7.0.57 ${CATALINA_HOME}
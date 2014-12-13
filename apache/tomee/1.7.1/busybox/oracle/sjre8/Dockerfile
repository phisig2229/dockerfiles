FROM	phisig2229/bb_oracle-sjre8

ENV		CATALINA_HOME /opt/tomee/active
ENV		TOMEE_INSTALL /opt/tomee

RUN		mkdir -p ${TOMEE_INSTALL} && \
		wget -qO- "http://archive.apache.org/dist/tomee/tomee-1.7.1/apache-tomee-1.7.1-webprofile.tar.gz" | tar -zx -C ${TOMEE_INSTALL} && \
		mv ${TOMEE_INSTALL}/apache-tomee-webprofile-1.7.1 ${CATALINA_HOME}
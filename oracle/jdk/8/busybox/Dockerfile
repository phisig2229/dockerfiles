FROM	phisig2229/bb:ubuntu-14.04

ENV		JAVA_HOME /java

RUN		wget -qO- --no-check-certificate --no-cookies --header "Cookie: oraclelicense=accept-securebackup-cookie" "http://download.oracle.com/otn-pub/java/jdk/8u25-b17/jdk-8u25-linux-x64.tar.gz" | tar -zx -C / && \
		mv jdk1.8.0_25 ${JAVA_HOME} && \
		rm ${JAVA_HOME}/*src.zip

ENV		PATH /sbin:/bin:/java/bin
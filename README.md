# docker-tomcat-server
Using docker-compose to deploy Tomcat server in Docker .

## environment path 

		CATALINA_BASE:   /usr/local/tomcat
		CATALINA_HOME:   /usr/local/tomcat
		CATALINA_TMPDIR: /usr/local/tomcat/temp
		JRE_HOME:        /usr
		CLASSPATH:       /usr/local/tomcat/bin/bootstrap.jar:/usr/local/tomcat/bin/tomcat-juli.jar

## how to use

* run 	

		./build-image.sh

* run 

		docker-compose up -d 

	Open your browser , and visit http://localhost:8080					
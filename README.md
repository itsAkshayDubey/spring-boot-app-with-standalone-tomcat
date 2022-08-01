# Spring Boot App With Standalone Tomcat Server

Purpose of this repository is to demostrate how to deploy a spring boot application on a standalone tomcat server instead of using embedded tomcat server that comes OOB with spring boot.

## How to deploy

1. Clone this repo
2. cd spring-boot-app-with-standalone-tomcat
3. mvnw.cmd clean clean  
4. Download and unzip tomcat from here: https://tomcat.apache.org/download-90.cgi
5. Copy spring-boot-with-standalone-tomcat.war from spring-boot-app-with-standalone-tomcat/target to webapps folder inside unzipped tomcat folder
6. Go to bin folder inside unzipped tomcat folder
7. catalina.cmd run

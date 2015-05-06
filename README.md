# COMP5347A2

##Applied technology
Struts2, Ajax, REST, Third-party APIs(Flickr), mysql

##Aroject specification
refer to Assignment.pdf

##Aequirement to run the project
Two different Tomcat server
Sql server

##How to run
1.execute A2.sql script in mysql server
2.config two seperate Tomcat server
  one for front end:
  Tomcat Admin port number: 8005
  HTTP/1.1 port number: 8090
  AJP/1.3 port number: 8009
  another for shiping component
  Tomcat Admin port number: 9005
  HTTP/1.1 port number: 9000
  AJP/1.3 port number: 9009
3.modify frontend and shipping pom.xml individually
in order to match the tomcat dependencies to your own runtime target
4.build the project and deploy them to each server accordinglly

# Spring4MVCHelloWorldAnnotationDemo

## Please take care after the maven project created
- add the folder of src/main/java
- add the folder of src/test/java
- add the folder of src/test/resources
- remove web.xml
- remove the index.jsp if needed.

## modify pom.xml
- add the servlet and jsp and scope provieded.
- add the tomcat plugin.
- add war plugin ignore the missing web.xml

## run the code 
- mvn clean install tomcat7:run
- open a browser localhost:8080
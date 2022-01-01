# Java demo using jax-ws APIs

This demo illustrates how to develop a service use the "code first"
approach using the JAX-WS APIs.

## Build and run the demo using Maven

From the base directory of this sample (i.e., where this README file is
located), the pom.xml file is used to build and run the demo. 

Using either UNIX or Windows:

	mvn clean install

builds the demo and creates a WAR file for optional Tomcat deployment.

To remove the code generated from the WSDL file and the .class
files, run `mvn clean`.


## Deploy service (WAR) to Tomcat 

Manually copy the generated WAR file to the Tomcat webapps folder.
 
Prior to running the client it would be good to confirm the 
generated WSDL can be seen from a web browser at, assuming that tomcat is running at localhost:8080

	http://localhost:8080/jaxws-demo/services/hello_world?wsdl


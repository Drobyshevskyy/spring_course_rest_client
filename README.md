<h2>Overview</h2>
A simple client-side web application that makes HTTP requests to the REST service
<br>
<br>
The information from the body of HTTP responses is received by methods in our application
<br>
<br>
Class "Employee.java" is used to convert JSON to Java object
<br>
<br>
Class "Communication.java" is responsible for connection to the REST server. All CRUD operations are perfromed by this class
<br>
<br>
"App.java" class is a testing class that executes queries and checks the retuned result
<h3>Configuration</h3>
Project is created from Maven archetype "maven-archetype-quickstart"<br>
The configuration of Spring Container connection is the responsibility of file "MyConfig.java" of package "configuration"<br>

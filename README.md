# spring-boot-project-with-h2-db
Spring boot project with H2 memory database, performing create, delete, get and update operations. 
Handling spring boot way global exception handling and Swagger UI for Rest End points

# Access the H2 Database from Browser using below URL
http://localhost:2500/h2-console/login.jsp

# Access Swagger UI for testing Rest Url's
http://localhost:2500/swagger-ui.html

Underlaying server taken as Jetty in this project. If you want tomcat , comment the jetty dependency and remove tomcat exclusion tag from pom xml file.

# @ConfigurationProperties changes are added
Refer the changes in below files
EmployeeResource, ApplicationProperties and application yml file.

# ECommerce-Web-App
This was a project for CSE305: Principles of Database Systems. 
It was built in collaboration with Usman Ansari and Patrick Boucicault.
This web app allows for three types of users, an employee, a buyer and a seller. 
An employee has access to remove users and items from the Database. A buyer can buy
and review items and a seller can sell items. 

This application was built using Java, MySQL, JSP and Bootstrap.

## How to Run Using Eclipse IDE
Download the JSTL 1.2 and MySQL Connector Java 8.0 jar files. Place these in the WebContent > WEB-INF > lib directory.
Refresh the project.

Add the Apache Tomcat server runtime by right clicking the project and selecting "Build Path" and "Configure Build Path". Select "Add Library" then "Server Runtime". Finally, select "Apache Tomcat v8.0".

Enter URL, username and password for your MySQL database in src/mysql/DBConnection.java.

Run project on Server.

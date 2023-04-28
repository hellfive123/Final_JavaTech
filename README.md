# Final_JavaTech

With the rapid development of the 4.0 technology era, along with the increasing demand for easy and convenient shopping options for customers' tastes nowadays, the application of Information Technology in the field of sales is becoming more and more popular. Therefore, the issue is how to shorten administrative procedures, increase work efficiency, in order to facilitate buying and selling exchanges, and processing a large amount of information quickly, requiring us to have an appropriate management method.

From the above issues, our group will carry out the project: "Inventory Management Application" to solve the problems that have been raised. We hope to develop a web-based inventory management system to increase efficiency instead of the traditional management method.

The system that our group will build will be written in Java language, combined with a database using Hibernate, and using the Spring Boot Framework.

## Requirements

To run this project, you need to have the following software installed on your machine:

- Java JDK 17 or higher
- Maven 4.0 or higher

## Installation



To install and run this project, follow these steps:

1. Clone the project repository to your local machine using the following command <br />
  **git clone https://github.com/hellfive123/Final_JavaTech.git**

2. Navigate to the project directory: **cd Final_JavaTech**.

3. Create a database named **webapp**.

4. Extract the **webapp_database.zip** file containing in project folder. Then import SQL files into **webapp** database.

5. Account provided in database include <br />
   **User account**: ***test@gmail.com***, ***123*** <br />
   **Admin account**: ***admin@gmail.com***, ***123*** <br />
   
6. Edit the application.properties file in the src/main/resources folder to match your MySQL database configuration:
  **spring.datasource.url=jdbc:mysql://localhost:3306/webapp<br />**
  **spring.datasource.username=your_database_username<br />**
  **spring.datasource.password=your_database_password<br />**
  
7. Build the project using Maven: **mvn clean install**.

8. Run the project using Maven: **mvn spring-boot:run**.

9. The project should now be running on `http://localhost:8080/login`. You can access the web application by visiting this URL in your web browser.







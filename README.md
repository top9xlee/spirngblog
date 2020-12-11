Steps and Requirements to build and run the Project
1. Create Mysql database and execute

2. Change mysql username and password as per your installation

open src/main/resources/application.properties
change spring.datasource.username and spring.datasource.password as per your mysql installation
3. Run the app using maven

mvn spring-boot:run or src/main/java/com.spring.PersonalBlog/PersonalBlog:run
The app will start running at http://localhost:8080

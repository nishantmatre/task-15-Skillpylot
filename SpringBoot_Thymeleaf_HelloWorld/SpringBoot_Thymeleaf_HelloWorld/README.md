# Hello World with Spring Boot and Thymeleaf

This project implements the task shown in SkillPilots: build a "Hello World" web page using Spring Boot and Thymeleaf.

## Requirements
- Java 17 or later
- Maven 3.6+ (or use Maven Wrapper if you add one)

## Run in VS Code / terminal
1. Extract this ZIP file.
2. Open the extracted `SpringBoot_Thymeleaf_HelloWorld` folder in VS Code or IntelliJ IDEA.
3. Make sure Java 17+ and Maven are installed.
4. Open a terminal in the project folder.
5. Run:

   ```bash
   mvn spring-boot:run
   ```

6. Open your browser at http://localhost:8080

You should see **Hello World!**

## How the task requirements are met
1. `pom.xml` includes `spring-boot-starter-thymeleaf`.
2. `HomeController.java` maps `/` to the `index` Thymeleaf template.
3. `src/main/resources/templates/index.html` contains the greeting.
4. Run the app and verify it at `http://localhost:8080`.

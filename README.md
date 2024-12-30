Airline Booking Website Testing Project

Overview

This project focuses on automating the testing process for an airline booking website using industry-standard tools. It includes browser-based UI testing, backend unit testing, API testing, and Jenkins for continuous integration.


Features

•	Selenium WebDriver: Browser automation for end-user testing.
•	TestNG: Unit testing for backend components.
•	Postman: API testing for REST endpoints.
•	Jenkins: Automated testing pipeline for CI/CD.



Technologies Used

•	Languages: Java, JSON
•	Frameworks: Selenium, TestNG
•	Tools: Postman, Jenkins, Git, Maven
•	IDE: Eclipse






Project Structure

|-- src  
         |-- main  
                   |-- java  
	pageobjects  

|-- src  
         |-- main  
               |-- tests  
	testcases
|-- pom.xml  


Getting Started

1. Clone Repository
git clone https://github.com/prasadmadduru/Capstone
cd [Project Directory]

2. Prerequisites

Java 11+
Maven
Eclipse IDE
Browser Drivers (e.g., ChromeDriver, GeckoDriver)
Postman
Jenkins


3. Build Project
mvn clean install

4. Run Tests

Selenium Tests
mvn test
TestNG Tests
Run testng.xml from the IDE.
Postman Tests

1. Import the Postman collection from the postman/ folder.
2. Execute test cases in Postman.





Jenkins Configuration

1. Add a new Jenkins job for the project.
2. Use the following script in the build step:
mvn clean test
3. Set up triggers for automated execution.


Testing Scenarios

Selenium:

Flight search form validation
Registration page automation
Booking confirmation page testing


TestNG:

Backend validation for flight and booking logic


Postman:

Get flights for a specific date
Get booked seats for a flight


Challenges and Solutions

Dynamic Elements: Handled using Selenium waits.

Jenkins Builds: Fixed dependency issues in pom.xml.



Future Scope

•	Add load testing using JMeter.

•	Increase test coverage for edge cases.

•	Implement cross-browser and device testing.




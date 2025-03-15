# rSystem
## Overview
This repository contains the testing documentation and automation scripts for WriteWave, a collaborative writing platform. The primary focus was to test the application, document issues, and collaborate with developers to enhance product quality.
## Table of Contents
Test Plan & Execution
Bug Reports & Collaboration
Automation Testing
## Test Plan & Execution
A test plan was created to cover the key functionalities of WriteWave, including:
Document Creation
User Authentication & Authorization (registration, login )
File Export & Sharing (saving and downloading documents)
UI Responsiveness (mobile, tablet, and desktop testing)
https://docs.google.com/document/d/1dHRlzYRaCspolPIehGcM5hLap15TkhE4ILjoL6nE3I0/edit?usp=sharing
## Bug Documentation
15+ bugs were identified and documented with detailed reproduction steps, screenshots, and impact analysis.
Find all reported bugs in https://docs.google.com/spreadsheets/d/1ALDerrDpIMdsu7ii8QZFIal5k9mJuR_-xw3Z3DyUeUA/edit?usp=sharing
## Automation Testing
5 Selenium test scripts were written to validate critical user flows, using the Page Object Model (POM) for maintainability.
Tested Scenarios:
Login & Authentication
Creating and Saving a Document
Exporting Content as a File
Testing Real-time Collaboration
Automation scripts are in the C:\Users\LENOVO\vikrantworkspace\RSystem folder.
## Tech Stack
Language: Java
Framework: Selenium + TestNG
Design Pattern: Page Object Model (POM)
## Repository Structure
📂 WriteWave-Testing  
 ├── 📂 test-documents  
 │   ├── test_plan.md  
 │   ├── bugs_report.md  
 │   ├── bug_reports/  
 │       ├── bug1.md  
 │       ├── bug2.md  
 │       ├── bug3.md  
 │  
 ├── 📂 automation-scripts  
 │   ├── pom/  
 │   │   ├── LoginPage.java  
 │   │   ├── CreatePostPage.java  
 │   │   ├── DashboardPage.java  
 │   ├── tests/  
 │   │   ├── BaseTest.java  
 │   │   ├── CreatePostTest.java  
 │   │   ├── LoginTest.java  
 │  
 ├── README.md   
 ├── pom.xml (for Maven dependencies)  

 ## Contact
Email: vikrantsheoran@gmail.com


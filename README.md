# rSystem
## Overview
This repository contains the testing documentation and automation scripts for WriteWave, a collaborative writing platform. The primary focus was to test the application, document issues, and collaborate with developers to enhance product quality.
## Table of Contents
Test Plan 
Test Cases
Test Scenarios
Bug Reports & Collaboration
Automation Testing
## Test Plan & Execution
A test plan was created to cover the key functionalities of WriteWave, including:
Document Creation
User Authentication & Authorization (registration, login )
File Export & Sharing (saving and downloading documents)
UI Responsiveness (mobile, tablet, and desktop testing)
https://docs.google.com/document/d/1dHRlzYRaCspolPIehGcM5hLap15TkhE4ILjoL6nE3I0/edit?usp=sharing
## Test Cases
https://docs.google.com/spreadsheets/d/14losYsClg8qfAMvjkImjev7UQzcJAWx6WFAtRM0NzMI/edit?usp=sharing
## Test Scenarios
https://docs.google.com/spreadsheets/d/1fIHQnTBvQmMxpm1EpZjPCdEIAGA51-UzOfNmvh7XRQs/edit?usp=sharing
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
Automation scripts are in the  folder.
## Tech Stack
Language: Java
Framework: Selenium + TestNG
Design Pattern: Page Object Model (POM)
## Repository Structure
📂 WriteWave-Testing  
 ├── 📂 test-documents  
 │   ├── test_plan.md  
 │   ├── test scenario.md  
 │   ├── bug_reports 
 │  
 ├── 📂 automation-scripts  
 │   ├── pom/  
 │   │   ├── LoginPage.java (https://drive.google.com/file/d/1faUlastT5T-zQu3nb1kUlS5wZH0SCtg8/view?usp=sharing) 
 │   │   ├── CreatePostPage.java (https://drive.google.com/file/d/15sYcCs2U8nXBbKioi2llWDKRMBeOt9hR/view?usp=sharing)
 │   │   ├── DashboardPage.java (https://drive.google.com/file/d/1OVkkQ6jhXBmffEYdcrnuXL5Jry6LOR96/view?usp=sharing)
 │   ├── tests/  
 │   │   ├── BaseTest.java (https://drive.google.com/file/d/1utkIFUyQUzXFEBLBG4YGDKc_1CS2KJmP/view?usp=sharing)
 │   │   ├── CreatePostTest.java (https://drive.google.com/file/d/12C3T6Y0op0lL_gOoJhif1yHdj6bjGvjc/view?usp=sharing)
 │   │   ├── LoginTest.java (https://drive.google.com/file/d/1rCRMGBWyiwB2u7H61aQzuqVjn-H0TcBQ/view?usp=sharing)
 │  
 ├── README.md   
 ├── https://drive.google.com/file/d/1hVZooHopv42nFuw9OlG_gYtpRE-fFPSl/view?usp=sharing( Pom.xml (for Maven dependencies)

 ## Contact
Email: vikrantsheoran@gmail.com


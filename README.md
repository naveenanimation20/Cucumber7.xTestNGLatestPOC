# Cucumber7.xTestNGLatestPOC
Cucumber7.xTestNGLatestPOC

This repository contains a Proof of Concept (POC) for running Cucumber tests in parallel using TestNG with Cucumber 7.x. The project demonstrates how to set up and configure your test framework to execute Cucumber scenarios in parallel with TestNG.

# Prerequisites
Java 8 or higher
Maven 3.x

# Project Structure

├── src
│   ├── main
│   │   └── java
│   │       └── com
│   │           └── example
│   │               └── pages
│   │                   └── LoginPage.java      # Page Object class for Login Page
│   └── test
│       ├── java
│       │   └── com
│       │       └── example
│       │           └── stepdefinitions
│       │               └── LoginSteps.java     # Step definitions for Login.feature
│       │           └── TestRunner.java         # Test runner class
│       └── resources
│           ├── features
│           │   └── Login.feature              # Cucumber feature file
│           └── testng.xml                     # TestNG configuration file
├── pom.xml                                     # Maven POM file with dependencies and plugins
└── README.md                                   # This README file


# Usage
Clone the repository:
git clone https://github.com/naveenanimation20/Cucumber7.xTestNGLatestPOC.git

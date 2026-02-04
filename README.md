Java Batch Final Project – Milestone 4
📌 Project Overview

This project is a Java-based Test Automation Framework developed as part of the Java Batch Milestone Four assessment.
The framework is built using Agile methodology, managed with Maven, and follows the Page Object Model (POM) design pattern to ensure scalability, maintainability, and reusability of test cases.
Development Methodology

The project was developed using Agile practices, with work divided into multiple sprints.
Each sprint focused on incremental delivery and improvement of the framework.

Sprint Activities Included:

Requirement analysis

Framework design and setup

Test case development

Test execution

Reporting and documentation

📄 Detailed sprint-wise execution and dates are documented in AGILE.md.

🛠 Technology Stack

Programming Language: Java

Build Tool: Maven

Automation Tool: Selenium

Test Framework: TestNG

Version Control: Git & GitHub

IDE: Eclipse IDE, IntelliJ IDEA

📁 Project Structure
Java-Batch-final-project/
│
├── Herokuapp/milestonefour/        # Main automation framework
│   ├── src/test/java/herokuapp/milestonefour
│   │   ├── basetest
│   │   ├── pages
│   │   ├── pagestest
│   │   ├── listeners
│   │   └── utility
│   │
│   ├── resources
│   │   └── config.properties
│   │
│   ├── pom.xml
│   └── testng.xml
│
├── four/                           # Maven wrapper setup
├── AGILE.md
├── LICENSE
└── README.md

▶️ Execution Guidelines
✅ Prerequisites

Java JDK 11 or higher

Maven

Git

🚀 Running the Test Suite

Navigate to the project directory and execute:

cd Herokuapp/milestonefour
mvn clean test

⚙️ Configuration Details

Application and environment settings are maintained in:
resources/config.properties

Test execution flow and suite management are controlled using:
testng.xml

📚 Documentation

Agile Sprint Documentation: AGILE.md

License: MIT License (LICENSE)

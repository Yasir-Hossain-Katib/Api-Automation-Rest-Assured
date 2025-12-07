# Automated API Testing with Rest Assured
## Project Description

This repository demonstrates complete API testing and automation for the Daily Finance application. The scope includes essential features such as user management and item management. All APIs were automated using Rest Assured, a widely-used Java library for API testing.

The testing workflow was organized into two main phases:

Postman Collection: Building and validating all required API requests.

Rest Assured Automation: Converting those same requests into automated test scripts with assertions.

Both positive and negative scenarios were implemented to ensure the APIs are reliable and handle errors correctly.

## Prerequisites

Make sure the following tools and libraries are installed:

- Java JDK (8 or later)

- Gradle (for dependency management)

- IntelliJ IDEA or any preferred Java IDE

- Postman (for initial API testing and inspection)

## What I Have Done
** Step 1: Exploring APIs with Postman

A dedicated Postman collection was created to test and understand the following endpoints:

- User Management APIs

   - Register a new user

   - Login as admin

   - Retrieve user list

   - Search user by ID

- Update user details (first name, phone number, etc.)

  - Login as a regular user

  - Item Management APIs

  - Get all item list

  - Add a new item

  - Edit an item

  - Delete an item

** Step 2: Automation Using Rest Assured

 - Automated all the above API flows using Rest Assured.

 - Added proper assertions to validate status codes, response bodies, and messages.

 - Implemented positive test cases to confirm expected behavior.

 - Included negative tests to verify proper error responses and validation handling.

## How to Run the Tests
Step 1: Clone the Repository
git clone <repository-url>

Step 2: Open the Project

Open the project in IntelliJ IDEA or any compatible Java IDE.

Step 3: Execute Test Scripts

Run the tests using TestNG through Gradle:

gradle clean test

Step 4: Review Test Results

After the execution finishes, detailed test logs and results will be generated, showing validations for each API endpoint.


## Test Case

https://docs.google.com/spreadsheets/d/1J46yH8MItgMmvrAKKzzJ02qTye8Gbj70CHRdIvDZHNg/edit?usp=sharing

## Allure Report Screenshot

![image](https://github.com/user-attachments/assets/6079f00d-2ce5-4165-b4a6-4e29256a59d0)


![image](https://github.com/user-attachments/assets/1cf70ea1-9a15-4e72-adc3-456f19e979ec)

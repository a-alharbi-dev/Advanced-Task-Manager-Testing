# Advanced Task Manager – Software Testing

A software testing project focused on evaluating an existing **Advanced Task Manager web application** as part of the **CCSW 323 – Software Testing** course.

The project focused on designing test cases, applying different testing models and coverage criteria, and evaluating the system using automated testing tools.

## 📌 Project Overview

The **Advanced Task Manager** was used as the **System Under Test (SUT)**.

The application is a web-based task manager that allows users to:

* Create an account and log in
* Add tasks
* Edit tasks
* Complete tasks
* Delete tasks
* Search and filter tasks
* Log out

The System Under Test was built using:

* HTML
* CSS
* JavaScript

The original application was obtained from an existing GitHub repository and was used for testing purposes.

##  Testing Models

The project applied two main testing models:

### 1. Input Space Testing

The following coverage criteria were applied:

* **Base Choice Coverage (BCC)**
* **Each Choice Coverage (ECC)**
* **Multiple Base Choice Coverage (MBCC)**

These techniques were used to identify different input characteristics and test valid, invalid, and empty input values.

### 2. Graph-Based Testing

The following coverage criteria were applied:

* **Node Coverage (NC)**
* **Edge Coverage (EC)**

The system was modeled using nodes and edges to represent different system states, actions, and transitions.

## 🔍 Test Cases

Test cases were designed for different system functions, including:

* User registration
* User login
* Login validation
* Adding tasks
* Completing tasks
* Editing tasks
* Deleting tasks
* Searching and filtering tasks
* Logout

The test cases included both valid and invalid input scenarios.

## 🤖 Test Automation

**Selenium WebDriver** and **JUnit** were used for automated testing.

### Selenium WebDriver

Selenium was used to:

* Open the web application
* Simulate user interactions
* Enter input data
* Click buttons
* Navigate through the application
* Verify system behavior

### JUnit

JUnit was used to:

* Execute test cases
* Compare expected and actual results
* Verify system behavior
* Determine whether test cases passed or failed

## 📊 Testing Results

A total of **28 test cases** were executed.

| Result       | Number |
| ------------ | -----: |
| ✅ Passed     |     28 |
| ❌ Failed     |      0 |
| 📊 Pass Rate |   100% |

All 28 executed test cases passed successfully.

## 🛠️ Tools & Technologies

* Selenium WebDriver
* JUnit
* Java
* HTML
* CSS
* JavaScript
* ChromeDriver
* Visual Studio Code
* NetBeans

## 📚 Project Documentation

This repository contains the documentation and presentation of the testing project.

The documentation includes:

* Testing models
* Coverage criteria
* Test case design
* Selenium and JUnit usage
* Test execution
* Testing results
* Project conclusion

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

* Software testing
* Test case design
* Input Space Testing
* Graph-Based Testing
* Coverage criteria
* Functional testing
* Automated web testing
* Selenium WebDriver
* JUnit
* Analyzing expected and actual results

## 👩🏻‍💻 Project Type

**Group Academic Project**

**Course:** CCSW 323 – Software Testing

**University:** Jeddah University

## 📎 Original System Under Test

The web application used for testing was obtained from an existing GitHub repository and was used only as the **System Under Test (SUT)** for this academic project.

Original repository:

https://github.com/11249a040-sandeep/todo-list-app

# 🚀 REST Assured API Test Framework | Scalable API Automation | Java | TestNG | REST Assured

<p align="center">

![Java](https://img.shields.io/badge/Java-REST%20Assured-red?style=for-the-badge&logo=openjdk)
![REST API](https://img.shields.io/badge/REST%20API-Automation-success?style=for-the-badge)
![TestNG](https://img.shields.io/badge/TestNG-Framework-red?style=for-the-badge)
![JSON](https://img.shields.io/badge/JSON-Validation-blue?style=for-the-badge)
![API Testing](https://img.shields.io/badge/API-Testing-orange?style=for-the-badge)
![GitHub](https://img.shields.io/badge/Open-Source-181717?style=for-the-badge&logo=github&logoColor=white)

</p>

---

# 📌 Project Overview

REST APIs are the backbone of modern web applications, microservices, and cloud-native systems. Building reliable API automation requires more than writing test scripts—it requires reusable design, robust validations, authentication handling, and maintainable test architecture.

This repository showcases a **scalable REST Assured API Automation Framework** built using **Java**, **REST Assured**, and **TestNG**, covering many of the concepts used in enterprise API automation projects.

The examples demonstrate real-world API testing techniques including authentication, API chaining, JSON schema validation, request payload management, POJO serialization, JsonPath extraction, and reusable test components.

---

# 🎯 Repository Objectives

This project demonstrates how to:

- Build scalable REST API automation using REST Assured
- Validate REST API responses effectively
- Implement authentication mechanisms
- Perform API chaining between requests
- Create reusable request payloads
- Deserialize JSON responses into POJOs
- Validate JSON schema
- Organize API automation projects using modular design

---

# 🚀 Key Features

✔ REST Assured API Automation

✔ TestNG Integration

✔ Authentication Examples

✔ API Chaining

✔ JSON Schema Validation

✔ JsonPath Examples

✔ POJO Serialization & Deserialization

✔ Request Payload Management

✔ Mock API Testing

✔ Data Sharing Between Requests

✔ Modular Project Structure

✔ Easy to Extend

---

# 🏗 Project Structure

```text
REST-Assured-API-Test-Framework-Scalable
│
├── src
│
│   └── test
│
│       └── java
│
│           ├── DataShare
│           │
│           ├── JsonPathSession
│           │
│           ├── LibertyBooking
│           │
│           ├── MockData
│           │
│           ├── Payloads
│           │
│           └── PoJoExamples
│
├── test-output
│
├── pom.xml
│
├── testng.xml
│
├── testngITestContext.xml
│
└── README.md
```

---

# 📚 Topics Covered

## 🔐 Authentication

Examples included:

- Basic Authentication
- Bearer Token Authentication
- OAuth 2.0 Authentication

These examples demonstrate secure API testing techniques commonly used in enterprise applications.

---

## 🔄 API Chaining

Real-world API automation frequently depends on values generated from previous requests.

Examples include:

```
Create User
      │
      ▼

Extract User ID

      │
      ▼

Use User ID in Next API

      │
      ▼

Validate Response
```

This repository demonstrates how to extract IDs, tokens, and other dynamic values using REST Assured.

---

## 📄 JSON Schema Validation

Validate response structures using JSON Schema.

Example:

```java
body(matchesJsonSchemaInClasspath("schemas/user-schema.json"));
```

Benefits:

- Detect API contract changes
- Improve response validation
- Reduce false positives

---

## 📦 Request Payload Management

Request payloads are organized into reusable Java classes.

Benefits:

- Cleaner code
- Easier maintenance
- Better scalability
- Reusable objects

---

## 🔎 JsonPath Examples

Extract values from API responses using JsonPath.

Examples include:

- IDs
- Tokens
- Nested Objects
- Arrays

---

## ☕ POJO Serialization & Deserialization

This project demonstrates:

- Java Object → JSON
- JSON → Java Object

A common enterprise practice for API automation frameworks.

---

## 🧪 Mock API Testing

Examples using mock data allow learning and experimentation without depending on live production APIs.

---

# ⚙ Technology Stack

| Category | Technology |
|-----------|------------|
| Language | Java |
| API Testing | REST Assured |
| Test Framework | TestNG |
| Build Tool | Maven |
| JSON Parsing | JsonPath |
| Serialization | POJO |
| Version Control | Git |
| Repository | GitHub |

---

# 💡 Skills Demonstrated

This repository showcases experience with:

- REST API Testing
- REST Assured
- Java
- TestNG
- API Authentication
- OAuth2
- Bearer Tokens
- Basic Authentication
- API Chaining
- JsonPath
- JSON Schema Validation
- POJO Mapping
- Payload Management
- Modular Framework Design

---

# ▶️ Running the Project

## Clone Repository

```bash
git clone https://github.com/ArpitChoubey/REST-Assured-API-Test-Framework-Scalable.git
```

---

## Install Dependencies

```bash
mvn clean install
```

---

## Execute Tests

```bash
mvn clean test
```

or execute using

```
testng.xml
```

---

# 📊 Reports

After execution, TestNG generates reports inside:

```
test-output/
```

Includes:

- HTML Report
- Passed Tests
- Failed Tests
- Execution Summary

---

# 🎯 Learning Outcomes

After exploring this repository, you will understand:

- Enterprise REST API automation
- Authentication handling
- REST Assured best practices
- JSON Schema Validation
- API Chaining
- POJO Mapping
- JsonPath
- Modular API Framework Design

---

# 💼 Ideal For

This repository is useful for:

- QA Automation Engineers
- API Automation Engineers
- Software Development Engineers in Test (SDETs)
- Java Developers
- Manual Testers moving to Automation
- Students preparing for API Automation Interviews

---

# 🚀 Future Enhancements

Planned additions include:

- Extent Reports
- Allure Reports
- Log4j2 Integration
- Data-Driven Testing
- Excel Integration
- Jenkins Pipeline
- GitHub Actions CI/CD
- Docker Execution
- Parallel API Execution
- Environment Configuration
- Request Specifications
- Response Specifications

---

# 👨‍💻 About the Author

## Arpit Choubey

**SDET | QA Automation Engineer | Java | REST Assured | Selenium | Playwright | Appium | TestNG | Maven | SQL | Jenkins**

Passionate about building scalable automation frameworks, exploring modern testing practices, and sharing practical learning resources with the QA community.

---

# 🌐 Connect With Me

### GitHub

https://github.com/ArpitChoubey

### LinkedIn

https://www.linkedin.com/in/arpitchoubey/

### Medium

https://medium.com/@ArpitChoubey9

---

# ⭐ Support

If you found this repository helpful, please consider giving it a **Star ⭐**.

Your support encourages me to continue building open-source automation frameworks and learning resources for the QA community.

---

## 💡 *"Great API automation is not just about sending requests—it's about building scalable, maintainable, and reliable test solutions that ensure software quality."*

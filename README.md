REST-Assured API Automation

A lightweight and modular API Automation Framework using REST Assured + TestNG.
Covers API best practices like Authentication, JSON Schema Validation, Chaining, and Reporting.

🚀 Features
✔ TestNG Integration

Organized test execution with testng.xml, annotations, parallel runs, and structured suites.

✔ Authentication

Examples include:

Basic Auth

Bearer Token

OAuth2 Token flow

✔ JSON Schema Validation

Validates API responses using

body(matchesJsonSchemaInClasspath("schemas/user-schema.json"));

✔ API Chaining

Create → Extract → Use in next request (ID, Token, etc.)
Ensures real-world end-to-end flow execution.

✔ Reporting

TestNG default HTML report → test-output/index.html

Supports Allure / Extent Reports (optional)

📁 Project Structure
src/test/java/
 ├─ DataShare
 ├─ JsonPathSession
 ├─ LibertyBooking
 ├─ MockData
 ├─ Payloads
 └─ PoJoExamples

test-output/    # TestNG Reports
pom.xml

▶️ How to Run
mvn clean test

👨‍💻 Author

Arpit Choubey — SDET | QA | Automation Engineer
🔗 LinkedIn | Medium

⭐ Support

If this repository helped you, please Star ⭐ the repo!

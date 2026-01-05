# SauceDemo Web Automation Framework

This project is a web test automation framework built to automate and validate core user flows of the SauceDemo application.  
It is designed using Selenium WebDriver, TestNG, and the Page Object Model (POM) to ensure maintainability, scalability, and clean test design.

---

## 🔍 Project Overview

The framework focuses on automating critical end-to-end scenarios such as login, product selection, cart operations, and checkout flow.  
It follows best practices in test automation, separating test logic from UI locators and supporting easy maintenance as the application grows.

---

## 🛠 Tech Stack

- Java  
- Selenium WebDriver  
- TestNG  
- Maven  
- Page Object Model (POM)  
- Allure Reporting  

---

## 🏗 Framework Architecture

- **Pages**: Contains page classes with locators and actions for each web page  
- **Tests**: Test classes that implement test scenarios using page methods  
- **Base**: WebDriver setup and test initialization  
- **Utils**: Configuration handling and shared utilities  

This structure improves readability, reduces duplication, and supports scalability.

---

## ✅ Covered Test Scenarios

- User login with valid credentials  
- Product listing validation  
- Add products to cart  
- Cart verification  
- End-to-end checkout flow  
- Logout functionality  

---

## ▶️ How to Run Tests

1. Clone the repository:
```bash
git clone <https://github.com/OZayed2023/saucedemo-web-automation_testing_using_selenium.git>
```
2. Navigate to the project directory:
```bash
cd project-folder
```
3. Run tests using Maven:
```bash
mvn clean test
```
---

## 📊 Test Reports

- Allure is used for test reporting.
- After running tests, generate the report using:
```bash
  allure serve allure-results
```

---

## 📝 Notes

- The framework follows Page Object Model to enhance test maintainability.
- Test data and configuration are externalized where applicable.
- The project is intended for learning, practice, and portfolio demonstration purposes.

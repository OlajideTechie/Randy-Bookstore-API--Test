# API Automation Framework

This automation test suite is built with **Javascript**, **Postman**, **Newman**, and **Allure**. Designed to automate testing for  **Randy's Bookstore API**, this project includes CI integration (Jenkins).

## 🚀 Tech Stack

- **[PostmanMockServer]** – API Base Url
- **[Javascript](https://www.typescriptlang.org/)** – Test Script
- **[Allure Reporter](https://webdriver.io/docs/allure-reporter/)** – Test reporting
- **[Jenkins]** – CI for test execution

## 📁 Folder Structure
```
project-root/
│
├── tests/
│   └── Randy_Bookstore.json
├── allure-results/        
├── allure-report/          ← Allure generates the final report here
├── config/
│   └── config.yml
```


# ⚙️ Setup & Installation

1. Clone the repository
    ```
    git clone https://github.com/OlajideTechie/Randy-Bookstore-API--Test.git
    cd Randy-Bookstore-API
    cd tests/
    ```
2. Install dependencies
    ```
    npm install
    ```


# ▶️ Running Tests

Run API Tests
```
npm run api_test
```


# 📊 Allure Report
```
- Reports are stored in reports/allure-report/
```



# 🔁 Jenkins CI
```
CI is configured to run tests on every push to main.
```


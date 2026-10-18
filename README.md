# VTiger CRM Automation Testing Project

## 📌 Project Overview

The **VTiger CRM Automation Testing Project** is a test automation project developed using Selenium WebDriver with Java. The purpose of this project is to automate functional test cases for the VTiger CRM application and improve testing efficiency, reliability, and test coverage.

This project demonstrates practical knowledge of web application automation, test execution, test scripts, and automation framework concepts.

## 🎯 Project Objectives

- Automate important functional workflows in VTiger CRM.
- Validate application behavior against expected results.
- Reduce repetitive manual testing efforts.
- Improve test coverage and reliability.
- Practice Selenium WebDriver automation using Java.

## 🛠️ Technologies and Tools

| Technology | Purpose |
|---|---|
| Java | Programming language |
| Selenium WebDriver | Web browser automation |
| TestNG | Test execution and test management |
| Maven | Dependency and project management |
| Git | Version control |
| GitHub | Source code hosting |
| Eclipse IDE | Development environment |

*Update this list if your project uses additional tools such as Apache POI, Log4j, Extent Reports, or Jenkins.*

## ✨ Key Features

- Automated browser interactions using Selenium WebDriver.
- Web element identification using Selenium locators.
- Functional test execution for selected VTiger CRM modules.
- Test organization and execution using TestNG.
- Maven-based dependency management.
- Version control and project collaboration using Git and GitHub.

## 📂 Project Structure

The exact structure may vary depending on your implementation.

```text
Vtiger_Automation_Selenium_Project/
│
├── src/
│   ├── main/
│   └── test/
│
├── pom.xml
├── testng.xml
└── README.md
```

## ⚙️ Prerequisites

Install the following tools before running the project:

1. Java JDK
2. Eclipse IDE or another Java IDE
3. Maven
4. Google Chrome or another supported browser
5. Git

Verify Java and Maven installation:

```bash
java -version
mvn -version
git --version
```

## 🚀 Setup and Installation

### Step 1: Clone the repository

```bash
git clone https://github.com/prashant-kit/Vtiger_Automation_Selenium_Project.git
```

### Step 2: Open the project folder

```bash
cd Vtiger_Automation_Selenium_Project
```

### Step 3: Import into Eclipse

1. Open Eclipse IDE.
2. Select **File → Import**.
3. Choose **Maven → Existing Maven Projects**.
4. Select the cloned project folder.
5. Click **Finish**.

### Step 4: Update Maven dependencies

Run the following command in the project directory:

```bash
mvn clean install
```

### Step 5: Execute the tests

If your TestNG suite is configured in `testng.xml`, you can run it through Eclipse by right-clicking the file and selecting **Run As → TestNG Suite**.

Alternatively, use Maven if the project is configured with a TestNG-compatible test plugin:

```bash
mvn test
```

## 🧪 Testing Scope

The following are examples of test areas that can be automated, depending on the scripts implemented in this project:

- Login and logout functionality
- Navigation between CRM modules
- Form submission and validation
- Creation, editing, and viewing of CRM records
- Positive and negative test scenarios
- Validation of expected results

Only mark a test area as automated after confirming that its test script exists and runs successfully.

## 📈 Skills Demonstrated

- Selenium WebDriver
- Core Java
- TestNG
- Maven
- Web element locators
- XPath and CSS selectors
- Test case design and execution
- Functional testing
- Debugging and defect identification
- Git and GitHub

## 🔮 Future Enhancements

- Implement the Page Object Model (POM), if not already present.
- Add data-driven testing.
- Improve test reporting and logging.
- Integrate automated execution with Jenkins.
- Expand test coverage for additional CRM modules.

## 👨‍💻 Author

**Prashant Singh**

GitHub: [prashant-kit](https://github.com/prashant-kit)

Project Repository: [VTiger CRM Automation Testing](https://github.com/prashant-kit/Vtiger_Automation_Selenium_Project)

## 📄 Disclaimer

This project is intended for educational and testing purposes. VTiger is a third-party product. This repository is an independent automation project and is not an official VTiger product or endorsement.

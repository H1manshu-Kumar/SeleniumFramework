# SeleniumFramework

&#x20;&#x20;

A robust Selenium-based automation testing framework using Java, TestNG, and Page Object Model (POM) to facilitate efficient UI test automation.

## 🚀 Features

- **Page Object Model (POM)** for maintainability
- **TestNG framework** for test execution & reporting
- **Cross-browser testing** with WebDriverManager
- **Data-driven testing** using Apache POI
- **Logging & Reporting** with Log4j & ExtentReports
- **Maven build management**
- **Parallel test execution** support

## 🛠️ Technologies Used

- **Language:** Java 11+
- **Framework:** Selenium WebDriver, TestNG
- **Build Tool:** Maven
- **Reporting:** ExtentReports, Log4j
- **Data Handling:** Apache POI (Excel)

## 📌 Prerequisites

- Install **Java 11+**
- Install **Maven**
- Set up **Chrome/Firefox WebDriver**

## 📂 Project Structure

```
SeleniumFramework/
│-- src/
│   ├── main/java/com/framework/
│   │   ├── base/ (Base classes)
│   │   ├── pages/ (Page Objects)
│   │   ├── utils/ (Utility classes)
│   ├── test/java/com/framework/
│   │   ├── tests/ (Test Cases)
│-- testng.xml (TestNG configuration)
│-- pom.xml (Maven dependencies)
│-- README.md (Project Documentation)
```

## ⚙️ Installation & Setup

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/H1manshu-Kumar/SeleniumFramework.git
   cd SeleniumFramework
   ```
2. **Install Dependencies:**
   ```sh
   mvn clean install
   ```
3. **Run Tests:**
   ```sh
   mvn test
   ```

## 📊 Reporting

- **ExtentReports:** Generates HTML reports under `test-output/`
- **TestNG Reports:** View test execution details in `test-output/index.html`

## 🤝 Contributing

Contributions are welcome! Follow these steps:

1. Fork the repository.
2. Create a new branch (`feature-branch`)
3. Commit your changes.
4. Push to your fork & submit a Pull Request.

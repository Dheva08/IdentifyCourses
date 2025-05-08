
# IdentifyCourses 📚  
**Automated Course Data Extraction from Coursera**

A robust testing and data extraction automation project that uses **Selenium WebDriver (UI)** and **Automation Framework** to identify Coursera courses based on search criteria. Extracts key course details like title, Duration(s), and rating. Designed for scalable execution with **TestNG**, **Extent Reports**, **Log4j 2**, and supports **parallel browser testing**.

---

## 🚀 Key Features

- 🔍 **Automated course search and filtering** on Coursera
- 📋 Extracts:
  - Course Title
  - Duration
  - Ratings
  - Languages and levels with count 
- 📊 **Detailed Test Reports** using Extent Reports
- 📘 **Comprehensive Logging** with Log4j 2
- 🧪 **Parallel Test Execution** using Selenium Grid and TestNG

---

## 🛠️ Tech Stack

- Java
- Selenium WebDriver
- Apache POI
- POM
- TestNG
- Extent Reports
- Log4j 2
- Automation framework

---

## ⚙️ Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/IdentifyCourses.git
cd IdentifyCourses
````

### 2. Build the Project

Use **Maven**:

```bash
mvn clean install
```

Or **Gradle** (if configured):

```bash
gradle build
```

### 3. Run TestNG Suite

You can run the TestNG test suite using:

```bash
mvn test
```

Or directly from your IDE by right-clicking on the `testng.xml` file and selecting **Run**.

---

## 📂 Project Structure

```
IdentifyCourses/
│
├── src/
│   ├── main/java/
│   │   └── core classes (page objects, utils, logging)
│   └── test/java/
│       └── test scripts (UI & API tests)
│
├── testng.xml
├── pom.xml / build.gradle
├── logs/
├── reports/
└── README.md
```

---

## 📈 Reports & Logs

* 📄 **Extent Reports**: Generated inside `/reports`
* 🗃 **Log Files**: Available in `/logs`, configured via Log4j2 XML file

---

## 🔧 Configuration

* Supports **cross-browser and parallel testing**
* Customize search criteria and browser capabilities in `testng.xml` or the config utility

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙋‍♀️ Author

* **Dhevadharshini A**
  *Automation | Web Dev | AI Enthusiast*


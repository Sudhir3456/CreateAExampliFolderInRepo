 
<h1 align="center">🛒Opencart : UI Automation Framework</h1>
 
🚀The Opencart Automation Framework is a robust, scalable, and efficient Selenium-based test automation solution designed for validating key functionalities of the Opencart e-commerce platform. Built using Java, TestNG, and Maven, this framework leverages the Page Object Model (POM) for structured and maintainable test scripts.

### 🎯 Objectives
🚀 End-to-End Test Coverage: Automates user workflows, including registration, login, product search, cart management, and checkout. <br>
🔄 Data-Driven Testing (DDT): Uses Excel-based datasets for executing multiple test scenarios dynamically. <br>
🌐 Cross-Browser Compatibility: Supports Chrome, Firefox, Edge, and other major browsers for seamless testing. <br>
🛠 Modular & Scalable Design: Implements POM architecture for reusability and easy maintenance. <br>
📊 Custom Test Reports & Logs: Integrates TestNG Listeners to generate detailed execution reports and failure screenshots. <br>
⚡ Continuous Integration Ready: Configurable with Jenkins & CI/CD pipelines for automated test execution. <br>
🚀Designed for speed, reliability, and maintainability, this automation framework enhances test efficiency, bug detection, and overall software quality in e-commerce applications. <br>

![opencartFreamwork](https://github.com/user-attachments/assets/ad69a6e4-fcb6-41c6-b8ae-b9208bd38922)






 <h1 align="center">📂 Project Structure  :</h1>

![OpencardFolderstructure](https://github.com/user-attachments/assets/67cdb05a-764b-4b17-ba01-f528baa81d21)
 
  # 📝Folder Structure Overview :

 ```plaintext
com.opencartV121  
├── 🗂 src/test/java  
│   ├── 📌 com.opencartV121.pageObjects  # Page Object Model (POM) classes  
│   │   ├── 📝 AccountRegistrationPage.java   # Handles new user registration  
│   │   ├── 📌 BasePage.java                 # Common functions for all pages  
│   │   ├── 🛒 CheckoutPage.java             # Manages checkout process  
│   │   ├── 🏠 HomePage.java                 # Represents the homepage  
│   │   ├── 🔑 LoginPage.java                # Handles login functionality  
│   │   ├── 🚪 LogoutPage.java               # Manages user logout process  
│   │   ├── 👤 MyAccountPage.java            # Manages user profile actions  
│   │   ├── 🛍 ProductPage.java              # Handles product details & actions  
│   │   ├── 🔍 SearchResultsPage.java        # Manages search and filters  
│   │   ├── 🛒 ShoppingCartPage.java         # Handles cart operations  
│  
│   ├── ⚙ com.opencartV121.testBase         # Base setup for test execution  
│   │   ├── 🏗 TestBase.java                 # WebDriver initialization & teardown  
│  
│   ├── 🧪 com.opencartV121.testcases        # Test scripts for validations  
│   │   ├── ✅ AccountRegistrationTest.java   # Tests new user registration  
│   │   ├── 🔑 TC002_LoginTest.java          # Validates successful login  
│   │   ├── 🚫 TC003_InvalidLoginDDT.java    # Tests invalid login scenarios  
│   │   ├── 🔄 TC004_LoginTestDDT.java       # Validates multiple logins via DDT  
│   │   ├── 🚪 TC3_Logout.java               # Ensures logout functionality  
│   │   ├── 🔎 TC4_SearchProduct.java        # Tests product search  
│   │   ├── 🛒 TC5_AddToCart.java            # Verifies add-to-cart functionality  
│   │   ├── 🔄 TC6_EndToEndTest.java         # Complete checkout workflow test  
│  
│   ├── 🛠 com.opencartV121.utilities        # Utility classes for framework support  
│   │   ├── 📊 ExcelUtility.java             # Handles Excel-based data-driven testing  
│   │   ├── ⚙ ConfigReader.java             # Reads configuration from property files  
│   │   ├── 📝 TestListeners.java            # Implements TestNG listeners for reports  
│   │   ├── 🌐 WebDriverUtility.java         # Helper methods for WebDriver actions  
│  
├── 🗂 src/test/resources                    # Test resources like property files & datasets  
├── ☕ JRE System Library [JavaSE-1.8]        # Java runtime environment  
├── 📦 Maven Dependencies                     # Selenium, TestNG, and other libraries  
├── 📜 logs                                   # Logs for debugging  
├── 📑 reports                                # Test execution reports  
├── 📸 screenshots                            # Screenshots of failed test cases  
├── 📊 testData                               # Data files for test execution  
├── 📁 test-output                            # TestNG execution results  
├── ⚙ ACtestng.xml                           # TestNG suite configuration  
├── 🌍 crossbrowsertesting.xml                # Config for cross-browser testing  
├── 📜 master.xml                             # Master test execution configuration
```
 

   <h1 align="center">📂 Project Phases  :</h1>


| Phase-1: Implementation | Phase-2: Execution | Phase-3: Maintenance |
|--------------|-------------|------------|
| Create Maven Project                     |Run test cases with Maven pom.xml.                         |Creating repository in GITHUB.  |
| Update pom.xml                           |Run test cases through Maven CLI. (Command Line Interface) |Commit the project code in local repository. |
| Create Page Objects                      |Run test cases using run. bat.                             |Push the project code to GITHUB remote repository from local GIT repository. |
| Create Basic Test case                   |Run test cases using Jenkins. (using bat file)             |Addressing issues and updates to automation scripts.
| Add logs to test case                    |Review test results and identify defects.                  |Reporting on automation performance and improvements. 
| Read common values from properties file  |Defect logging and management
| Run test case on desired browser         |
| Add extent report                        |
| Create Data Driven test case             | 
| Adding new test case                     | 
  <h1 align="center">🌐 Technologies Used:</h1>

  - **Selenium WebDriver** is being used as the core automation engine.

- **Eclipse IDE** is used to develop the automated scripts.

- **Build tool Maven** is used for build, execution and dependency purpose.

- **TestNG framework** is used for organizing the scripts.

- **Page Object Model** as the design pattern.

- **Test data** is read from Excel sheet at run time.

- **Git and Github** is used for version control management.

- **Cl tool Jenkins** is used to run the scripts.

- **Extent Spark Report** test results are generated for each run.

<h1 align="center">✨ Key Features :</h1>

- >> Validates login, registration, product search, sorting, and cart management.
- >> Supports data-driven testing with Excel.
- >> Generates custom reports for test execution.
- >> Enables cross-browser and parallel test execution.



<h1 align="center">  💼 Reporting :</h1>


  ![OpemcardestReportwithimage](https://github.com/user-attachments/assets/f6535a46-a209-4c98-bdc2-215a53cf6f93)
 
  ![opencardreport1](https://github.com/user-attachments/assets/bfe9ac6f-f034-4d33-b923-29f2a680eff0)
 
- TestNG Reports :
  
![opencardreport](https://github.com/user-attachments/assets/4fcaf8e3-700e-4b5b-8acd-b884b219b96a)

 
 

 <h1 align="center">🤝 Contributing :</h1>

- Contributions are welcome! Feel free to submit issues and pull requests.
 



    

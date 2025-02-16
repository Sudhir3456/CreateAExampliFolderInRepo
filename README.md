 
<h1 align="center">🛒PetStore : API Automation Framework</h1>
 
🚀 A scalable and efficient API automation framework designed to validate and test PetStore web services, ensuring seamless integration, data integrity, and performance.


### 🎯 Objectives
✔ Automate end-to-end API testing with CRUD operations <br>
✔ Validate API responses and data accuracy <br>
✔ Implement data-driven testing for broader coverage <br>
✔ Generate detailed execution reports with Extent Reports <br>
✔ Enable CI/CD integration for continuous testing <br>
✔ Ensure modular, maintainable, and scalable framework design <br>
 
 ![PetstroreApiFreamwork](https://github.com/user-attachments/assets/7db2ada5-ceaa-4575-831e-08cf4f4a9a0d)



 <h1 align="center">📂 Project Structure  :</h1>

 ![petstrore](https://github.com/user-attachments/assets/4d3aacd8-9d43-4bf0-9fe4-8c0f79734ef7)
 # 📝Folder Structure Overview :

 ```plaintext
com.PetStoreAutomation
├── src
│   ├── test/java
│   │   ├── api.endpoints         # API endpoints handling
│   │   │   ├── Routes.java          # Defines API routes
│   │   │   ├── UserEndPoints.java    # User-related API operations
│   │   │   ├── UserEndPoints2.java   # Additional user API methods
│   │   ├── api.payload          # Payload classes
│   │   │   ├── User.java            # User data model
│   │   ├── api.test             # Test scripts for API testing
│   │   │   ├── DDTests.java         # Data-driven test cases
│   │   │   ├── UserTests.java       # Test cases for user API
│   │   │   ├── UserTests2.java      # Additional user API tests
│   │   ├── api.utilities        # Utility classes for test framework
│   │   │   ├── DataProviders.java      # Data providers for parameterized tests
│   │   │   ├── ExtentReportManager.java # Manages Extent Reports
│   │   │   ├── XLUtility.java         # Utility for Excel data handling
│   ├── test/resources
│   │   ├── log4j2.xml           # Log configuration
│   │   ├── routes.properties    # API routes configuration
├── logs
│   ├── automation.log           # Log file for test execution
├── reports
│   ├── Test-Report-2025.02.08.18.50.56.html  # Test execution report
│   ├── Test-Report-2025.02.08.18.52.02.html
│   ├── Test-Report-2025.02.08.19.02.11.html
│   ├── Test-Report-2025.02.13.20.04.17.html
├── testData
│   ├── Userdata.xlsx            # Excel file for test data
├── test-output                  # TestNG output reports
├── pom.xml                       # Maven dependencies
├── testng.xml                    # TestNG configuration file

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
 

- **Java (JDK 1.7+)** is being used as Programming language.

- **Eclipse IDE** is used to develop the automated scripts.

- **RestAssured** is used for API automation.

- **JSON** is used for JSON parsing.

- **Jackson/Gson** is used to develop the automated scripts.

- **Log4j2** is used for logging test execution details.

- **Apache POI** is used for logging test execution details Data Handling & Utilities.

- **Jackson/Gson** is used for reading/writing Excel test data.

- **Properties file** is used for configuration management.
 
- **Build tool Maven** is used for build, execution and dependency purpose.

- **TestNG framework** is used for organizing the scripts.
 
- **Test data** is read from Excel sheet at run time.

- **Git and Github** is used for version control management.

- **Cl tool Jenkins** is used to run the scripts.

- **Extent Spark Report** test results are generated for each run.

<h1 align="center">✨ Key Features :</h1>

- >> Modular Design: Structured packages for API endpoints, payloads, tests, and utilities.
- >>REST API Automation: Uses RestAssured for API testing (GET, POST, PUT, DELETE).
- >>Data-Driven Testing: Reads test data from Excel (Apache POI) and uses TestNG DataProviders.
- >> Hybrid Framework: Combines Data-Driven, Modular, and Utility-Based approaches.
- >> Configuration Management: Stores API routes in properties files for easy updates.
- >> Assertions & Error Handling: Uses TestNG assertions for response validation.
- >> Maven-Based Build: Manages dependencies and execution via pom.xml.
- >> Automated Test Reports: Saves execution logs and generates detailed HTML reports.



<h1 align="center">  💼 Reporting :</h1>

  - TestNG Reports :
   ![PetstroreReport](https://github.com/user-attachments/assets/4b0132ec-04ec-437b-bb2d-47074927b096)

    ![petsorereport](https://github.com/user-attachments/assets/1bae1c7e-5305-4e62-9e7d-b1369dc0e2e9)
 

 <h1 align="center">🤝 Contributing :</h1>

- Contributions are welcome! Feel free to submit issues and pull requests.
 



    

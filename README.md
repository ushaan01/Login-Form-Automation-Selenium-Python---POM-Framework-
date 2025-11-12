
📘 Project Overview: 
                    
This project automates the Techlistic Selenium Practice Form using Selenium WebDriver, PyTest, and the Page Object Model (POM) design pattern.

It demonstrates data entry, interaction with different form elements, and test result reporting with an HTML report. 


🧩 Features

Page Object Model (POM) structure for better maintainability

PyTest framework for test execution

pytest-html for report generation  

Data-driven test support


🏗️ Project Structure

├── base_pages/

│   └── login_form.py        # Page Object file containing web element locators & actions

├── test_cases/

│   └── automation.py        # Test case using PyTest

├── reports/

│   ├── report1.html         # Failed Test Report

│   └── report2.html         # Passed Test Report

├── requirements.txt         # Dependencies



🧠 Technologies Used

| Tool                        | Purpose                        |

| **Python**                    | Programming language           |

| **Selenium WebDriver**        | Browser automation             |

| **PyTest**                    | Test execution framework       |

| **PyTest-HTML**               | Test reporting                 |

| **Page Object Model (POM)**   | Test structure and maintenance |



✅ Test Scenario

Test Case: Automate Techlistic Practice Form

| Step | Action                                 |

| 1    |  Open Techlistic Practice Form          |

| 2    |  Enter first name and last name         |

| 3    |  Select gender and years of experience  |

| 4    |  Enter date                             |

| 5    |  Select profession and automation tools |

| 6    |  Choose continent and commands          |

| 7    |  Upload image                           |

| 8    |  Submit form                            |

🚀 How to Run the Project

Follow the steps below to set up and execute the automation tests:

 1️⃣ Clone the Repository

git clone https://github.com/ushaan01/Techlistic-Login-Form-Automation-POM-Project.git

2️⃣ Navigate to the Project Folder

cd Techlistic-Login-Form-Automation-POM-Project

3️⃣ Install Required Dependencies

pip install -r requirements.txt

4️⃣ Run the Tests

pytest

pytest --html=reports/report.html --self-contained-html

5️⃣ View the Report

reports/report.html


🧑‍💻 Author

Usha Nazare

| Project Type           | Practice Project  |

Automation Tester | Python + Selenium Enthusiast









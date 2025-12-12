# EMS Automation Testing Project

## 📌 Overview
This project contains automated test scripts for the **EMS (Employee Management System)** website. The automation framework is built using **Selenium** for browser automation and **Pytest** as the testing framework. The goal of this project is to validate the core functionalities of the EMS application through a scalable, maintainable, and reusable test automation suite.

---

## 🚀 Technologies Used
- **Python 3.x**
- **Selenium WebDriver**
- **Pytest**
- **pytest-html** (for test reports)
- **Virtual Environment (venv)**

---

## 📁 Project Structure
```
|-- tests/
|   |-- test_login.py
|   |-- test_add_employee.py
|   |-- test_update_employee.py
|   |-- test_delete_employee.py
|
|-- pages/
|   |-- login_page.py
|   |-- dashboard_page.py
|   |-- employee_page.py
|
|-- utils/
|   |-- driver_setup.py
|   |-- config.py
|
|-- reports/
|
|-- requirements.txt
|-- README.md
```

---

## ⚙️ Setup Instructions
### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/ems-automation.git
cd ems-automation
```

### 2️⃣ Create and activate a virtual environment
```bash
python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows
```

### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Tests
### Run all tests
```bash
pytest
```

### Generate HTML Report
```bash
pytest --html=reports/report.html --self-contained-html
```

---

## 🧪 Test Scenarios Covered
- ✔️ Login functionality
- ✔️ Add new employee
- ✔️ Update existing employee details
- ✔️ Delete employee record
- ✔️ Dashboard and navigation validation

---

## 🏗️ Framework Design
This project follows the **Page Object Model (POM)** architecture for better maintainability:
- Each page has a dedicated class inside the `pages/` directory.
- Test scripts call page methods, making tests clean and readable.
- Driver configuration and utility methods are handled in `utils/`.

---

## 📄 Reports
After running tests, HTML reports are generated inside the **reports/** directory. These reports include:
- Test summary
- Passed/failed/skipped tests
- Error logs and screenshots


## 📧 Contact
For any queries or suggestions:
**Email:** Krumi8955@gmail.com



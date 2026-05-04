# API Testing Framework – Restful Booker

A robust, scalable, and production-ready **API Automation Framework** built using **Python + Pytest** for testing the Restful Booker application.

This project demonstrates industry-level best practices including modular design, reusable utilities, structured test organization, and clean reporting.

---

## 📌 Project Overview

This framework automates end-to-end API testing for the **Restful Booker** application, covering:

* Authentication
* Booking creation
* Booking retrieval
* Booking update
* Booking deletion

It is designed to be:

* --> Reusable
* --> Modular
* --> Scalable
* --> Easy to maintain

---

## 🛠️ Tech Stack

* **Language:** Python
* **Framework:** Pytest
* **HTTP Client:** Requests
* **Reporting:** Pytest (extendable to Allure)
* **Design Pattern:** Modular Framework

---

## 📁 Project Structure

```
API-Framework_Restful-booker/
│
├── api/                # API request handling (endpoints)
├── core/               # Core configurations (base setup)
├── utils/              # Helper utilities (logger, common functions)
├── tests/              # Test cases
├── test_data/          # Test payloads and data
├── reports/            # Test execution reports
├── conftest.py         # Pytest fixtures (setup/teardown)
├── pytest.ini          # Pytest configuration
└── requirements.txt    # Dependencies
```

---

## ⚙️ Features

*  Structured API layer (separation of concerns)
*  Reusable request methods
*  Centralized configuration management
*  Pytest fixtures for setup/teardown
*  Logging support for better debugging
*  Scalable test design
*  Easy integration with CI/CD

---

## ️ How to Run Tests?

### 1. Clone the repository

```bash
git clone https://github.com/mona-lisha-doing-git/API-Framework_Restful-booker.git
cd API-Framework_Restful-booker
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run tests

```bash
pytest -v
```

---

## 🔬 Sample Test Flow

* Generate authentication token
* Create a booking
* Validate booking details
* Update booking
* Delete booking
* Verify deletion

---

## 📊 Reporting

Basic reports are generated using Pytest.
Planning to extend this framework with **Allure Reports** for advanced visualization.

---

##  Future Enhancements

*  Allure Reporting integration
*  CI/CD pipeline (GitHub Actions)
*  Data-driven testing (JSON/CSV)
*  Environment-based configuration
*  Parallel test execution

---

##  Key Highlights

* Follows **industry-standard automation practices**
* Clean and maintainable code structure
* Easily extensible for large-scale projects
* Suitable for **SDET / QA / Backend testing roles**

---

## 👩‍💻 Author

**Monalisha Kalita**
--> Aspiring Software Engineer | Strong in DSA & Automation

---

Thank you!

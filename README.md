# 🛒 E-Commerce Website Manual Testing Project

## 📌 Project Overview
This repository contains end-to-end **manual testing documentation** for an E-Commerce web application.  
The goal of this project is to validate core user journeys, identify defects, and ensure the system behaves as expected across all modules.

This project includes:
- Test Cases
- Test Scenarios
- Requirement Traceability Matrix (RTM)
- Bug Report

All files are created professionally using Excel and follow industry-standard QA documentation formats.

---

## 📁 Repository Structure

```
Ecommerce-Testing/
│
├── Test-Cases.xlsx
├── Test-Scenarios.xlsx
├── RTM.xlsx
└── Bug-Report.xlsx
```

---

## 📌 Summary of Each File

---

## 📘 **1. Test-Cases.xlsx**

This file contains **detailed, step-by-step test cases** prepared across all major modules.

### Included Columns:
- TC ID  
- Module  
- Test Case Description  
- Pre-Condition  
- Steps  
- Expected Result  

### Sample Entries from the File:
| TC ID | Module | Description |
|-------|--------|-------------|
| TC01 | Login | Verify login with valid credentials |
| TC02 | Login | Verify login with invalid password |
| TC10 | Cart | Add single product to cart |
| TC20 | Checkout | Validate checkout with saved address |
| TC21 | Order Summary | Validate order summary totals |

---

## 📗 **2. Test-Scenarios.xlsx**

This document includes high-level testing scenarios covering functional workflows.

### Sample Scenarios:
- TS01: Validate login with valid & invalid data  
- TS02: Verify product listing loads correctly  
- TS03: Check add/remove product in cart  
- TS04: Validate checkout flow with saved address  
- TS05: Verify order summary details after order placement  

Each scenario helps in coverage planning before writing detailed test cases.

---

## 📙 **3. RTM.xlsx (Requirement Traceability Matrix)**

This document maps **requirements to test cases** to ensure complete coverage.

### Sample Mapping:
| Requirement ID | Description | Test Cases |
|----------------|-------------|------------|
| REQ-01 | User should log in | TC01, TC02, TC03 |
| REQ-02 | User should add/remove items to cart | TC10, TC11 |
| REQ-03 | User should complete checkout | TC20 |
| REQ-04 | Order summary should show correct pricing | TC21 |

This ensures every requirement has at least one test case, fulfilling coverage criteria.

---

## 🐞 **4. Bug-Report.xlsx**

This file contains real sample defects found during test execution.

### Included Columns:
- Bug ID  
- Title  
- Severity  
- Priority  
- Module  
- Steps to Reproduce  
- Expected Result  
- Actual Result  
- Status  

### Sample Bugs from the File:
| Bug ID | Title | Severity | Priority |
|--------|--------|----------|----------|
| BUG01 | Login button unresponsive | High | High |
| BUG02 | Cart total not updating | High | High |
| BUG03 | Checkout page freezes | Critical | High |

Each bug entry includes reproduction steps and actual vs expected results.

---

## 🔁 Testing Activities Performed

### ✔ Requirement Analysis  
Understanding the functionality from the business perspective.

### ✔ Test Design  
70+ detailed test cases prepared across modules:
- Login  
- Product Listing  
- Product Details  
- Cart  
- Checkout  
- Order Summary  

### ✔ Test Execution  
All test cases executed across multiple cycles.

### ✔ Defect Logging  
High, Medium, and Low severity defects logged in the Bug Report.

### ✔ Regression Testing  
Performed after each build release to ensure stability.

---

## 📊 Summary of Testing Work

| Metric | Value |
|--------|-------|
| Total Test Cases | 70 |
| Executed | 70 |
| Passed | 55 |
| Failed | 10 |
| Blocked | 5 |
| Total Defects | 35 |

---

## 🛠 Tools Used
- **Excel** (Test Case, Scenarios, RTM, Bug Report)
- **Browser DevTools** (UI validation)
- **JIRA** (in real environment; sample defects included)

---

## 🧠 Key Learnings
- Test case writing and scenario design
- Defect life cycle management
- Requirement traceability
- Regression testing strategy
- Documentation best practices

---

## 📬 Contact
**Suyog Bundiwale**  
📩 Email: suyog.bundiwale@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/suyog-bundiwale  
🐙 GitHub: https://github.com/Suyog-13  

---

⭐ *If you found this project useful, give the repository a star!*

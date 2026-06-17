# ModernTech Solutions - HR Management System (Proof of Concept)

## Project Description
ModernTech Solutions is a rapidly growing software development company specializing in healthcare platforms. As the company scaled from 20 to 250 employees, its legacy HR processes—reliant on scattered Excel sheets, fragmented emails, and shared drives—became highly inefficient. 

This project is a **purely front-end, single-page web application** built as a proof of concept to demonstrate how ModernTech's HR workflows can be completely centralized, digitized, and automated. It provides an intuitive, responsive interface designed for non-technical HR staff to seamlessly manage records, automate payroll calculations, and track time-off requests.

---

## Key Features

### 1. Centralized Employee Data Management
* **Unified Directory:** Consolidates personal profiles, employment history, and financial data into a single searchable dashboard.
* **Pre-loaded Records:** Includes a minimum of 15 complete, detailed dummy employee records to demonstrate full operational functionality.
* **CRUD Simulations:** Allows HR staff to view, add, edit, and update employee details entirely on the client side using `localStorage` for data persistence.

### 2. Automated Payroll & Digital Payslip Generation
* **Automated Calculations:** Eliminates manual spreadsheet calculations by automatically computing gross pay, deductions, tax, and net pay based on pre-defined salary rates and hours worked.
* **Payslip Generator:** Dynamically generates clean, printable digital payslips for individual employees at the click of a button.

### 3. Attendance & Time-Off Tracking
* **Leave Management Request Hub:** Simulates employee time-off requests.
* **HR Approval Workflow:** HR staff can directly approve or deny requests, which automatically updates the employee's attendance logs and remaining leave balances in real time.

### 4. Advanced Enhancements (Bonus Features)
* **Mock Authentication:** A secure login simulator featuring hardcoded credentials for HR staff access control.
* **Client-Side Form Validation:** Real-time data validation on all entry forms to prevent empty fields, negative salaries, or malformed inputs.
* **Data Visualization:** Interactive dashboard charts showing attendance trends and departmental distributions using simulated data analytics.

---

## Technologies Used

* **Framework:** Vue.js (Progressive JavaScript Framework for reactive data binding and component architecture)
* **Styling & Responsiveness:** Bootstrap 5 (Ensuring fluid layouts across desktops, tablets, and smartphones)
* **Icons:** Bootstrap Icons / FontAwesome
* **Data Persistence:** Browser `localStorage` (To preserve changes across page reloads without a dedicated back-end database)

---

## Setup & Local Installation Instructions

Follow these steps to clone, run, and explore the project locally on your machine:

1. **Clone the Repository:**
```bash
   git clone [https://github.com/Yusuf106ismail/lca-course1-core-project.git](https://github.com/Yusuf106ismail/lca-course1-core-project.git)

# MotorPH-Payroll System
MO-IT103 | S1102 | Team Pochi - Subingsubing, G., Ramos, G., Moricilla, A., Melendrez, C., Militar, J.,

## Overview  
The Payroll System code created for MotorPH as part of our coursework is available in this repository.
It has features for tracking employee attendance, government deductions, payroll processing and login system.

## Submission for MO-IT103 – Computer Programming 2

- Subject: MO-IT103 – Computer Programming 2  
- Mentor: Aldwin Nunag  
- Term: Term 3, SY 2024–2025   
- Repository: https://github.com/Gexi0013/MotorPH-Payroll
- Mentor Email: anunang@mmdc.mcl.edu.ph added as collaborator  

## Class Diagram
![image (1)](https://github.com/user-attachments/assets/94731670-24d5-4d55-b836-18b3aa26bc1e)


## GUI Practice
![Screenshot 2025-05-24 154109](https://github.com/user-attachments/assets/22912a46-2623-4954-933d-f8463541e008)

# Missing Features
The code lacks:
    - Proper employee record management (create/view)
    - Data persistence (it doesn`t save records between runs)
    - Proper class structure for employees
    - Database or file storage integration

# Key Improvements:
  1. Employee Record Management:
     - Create/view employee records with additional details (Position, Department)
     - Proper employee class structure
  2. Data Persistence:
     - Saves employee data to file (employees.dat)
     - Loads data when program starts
  3. Structured Code:
     - Better organization of payroll calculations
  4. Maintained Original Functionality:
     - Keeps original time calculation logic
     - Preserves payroll calculation formulas
  5. Error Handling:
     - Basic file operation error handling
     - Input validation (through more could be added)

## MotorPH Employee Application with View, Create Record Functionalities and login system.

## New Updated Features

* Secure login system
  Username:
  Password:

* Employee Record Management (CRUD)
  - Create Employees: ID, Position, Department 		
  - Read: View all employees record
  - Update: Modify existing records
  - Delete: Remove employees records
  Persistent storage to employee.dat file

* Enhanced Time Tracking
  - Daily Attendance: Record time-in/time-out for each workday (Mon-Fri)
  - Auto-Calculation: Computes worked hours/minutes per day.
    
* Payroll Processing
   Automatic Calculations:
    + Gross Salary (Hourly rate: P142.86)
    + Allowances (rice, phone, clothing)
    + Deductions (SSS, PhilHealth, Pag-IBIG, Tax)
    + Net pay calculation

* Generates a payslip with:
  - Employee details
  - Breakdown of earnings and deductions
  - Net pay calculation
  - Date and time stamp

## Structure Summary
 MotorPH-Payroll/
  ├── src/
  │   ├── MotorPH.java          # Main class
  │   ├── Employee.java         # Data model
  │   └── LoginSystem.java      # Auth system
  ├── data/                     # Ignored in Git
  │   ├── employees.dat
  │   └── Payroll_Report
  └── README.md
  
## MO-IT103 - Computer Programming 2
Term 3  SY 2024 - 25  Bachelor of Science in Information Technology  S1102
Group Team Pochi

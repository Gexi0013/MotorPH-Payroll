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

## MotorPH Employee Application with View, Create Record Functionalities and login system.

## Features
* Secure login system
  - Username: 11025
  - Password: ******
    
<img width="543" height="505" alt="image" src="https://github.com/user-attachments/assets/1ca5416f-162d-4727-88b1-33de1ae89f93" />


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

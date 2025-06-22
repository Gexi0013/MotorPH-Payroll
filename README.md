# MotorPH-Payroll
# MotorPH-Payroll System
MO-IT103 | S1102 | Team Pochi - Subingsubing, G., Ramos, G., Moricilla, A., Melendrez, C., Militar, J., 

## Overview  
The Payroll System code created for MotorPH as part of our coursework is available in this repository.
It has features for tracking employee attendance, government deductions, and payroll processing.

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
  - Proper employee record managenment (create/view)
  - Data persistence (it doesn`t save records between runs)
  - Procer class strcture for employees
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
     - Preserves payroll calculation fomulas
  5. Error Handling:
     - Basic file operation error handling
     - Input validation (through more could be added)

## MotorPH Employee Application with View and Create Record Functionalities

## New Updated Features
# Employee Record Management
  - Create Employees: ID, Position, Department
  - View all employees record
  - Persistent storage to employee.dat file

# Enhanced Time Tracking
  - Daily Attendance: Record time-in/time-out for each workday (Mon-Fri)
  - Auto-Calculation: Computes worked hours/minutes per day.
    
# Payroll Processing
   Automatic Calculations:
    + Gross Salary (Hourly rate: P142.86)
    + Allowances (rice, phone, clothing)
    + Deductions (SSS, PhilHealth, Pag-IBIG, Tax)
    + Net pay calculation

# Generates a payslip with:
  - Employee details
  - Breakdown of earnings and deductions
  - Net pay calculation
  - Date and time stamp

## Structure Summary
    1. Employee Management   (Create/View)
    2. Time Tracking         (Daily logs)
    3. Payroll Calculator    (Auto-compute)
    4. Data Storage          (Save/Load)

## CRUD Operations
     Create: Add new employees
     Read: View all employees
     Update: Modify existing records
     Delete: Remove employees
  
## MO-IT103 - Computer Programming 2
Term 3  SY 2024 - 25  Bachelor of Science in Information Technology  S1102
Group Team Pochi



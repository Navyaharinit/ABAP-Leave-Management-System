# ABAP Leave Management System

This project is an SAP ABAP Module Pool application designed to manage employee leave requests, approvals, balances, and history using ALV reports.

## 🔹 Features

### Employee Module (Z130_Leave_REQ)
- Submit leave requests with:
  - Employee Number (F4 help)
  - Leave Type
  - Start and End Date
  - Reason
- Data stored in custom table `Z130_LEAVE_REQ`

### Manager Module (Z130_Leave_APP)
- View pending leave requests in ALV Grid
- Approve or Reject leave requests
- Automatic leave balance update
- Leave history display in ALV
- Optional email notification using CL_BCS

## 🔹 Technical Concepts Used

- Module Pool Programming
- Multiple Screens (0100, 0200, 0400, 0500)
- ALV Grid (CL_GUI_ALV_GRID)
- Custom Containers
- Custom Tables:
  - Z130_EMP_MASTER
  - Z130_LEAVE_REQ
  - Z130_LEAVE_BALE
- CRUD Operations
- Email Notifications (CL_BCS, CL_DOCUMENT_BCS)
- Smartform Attached to the mail
- Popup Confirmations

## 📂 Files in This Repository

- `Z130_Leave_APP.abap` → Manager approval program
- `Z130_Leave_REQ.abap` → Employee leave request program
- `Project_Report_ABAP_Leave_Management.pdf`
- `Test_Cases_ABAP_Leave_Management.pdf`

## 🎯 Academic Project

Developed as part of ABAP Programming coursework.  
Focus on real-world HR leave workflow automation using SAP.


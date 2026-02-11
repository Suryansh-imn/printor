# Printor
Automating printing requests using Flask

## Tech Stack
- HTML
- CSS
- JavaScript
- Python
- Flask-Python

## Features
- RBAC (Role Based Access Control)
- Print Workflow
- Printer Automation
- Log Access
- Fare Deduction
- File Conversion

### RBAC
The user types:
- Admins
- Replica users
- Students
Admins/Replica Users - Can approve/reject print requests.
Students - Can request print requests.

### Print Workflow

Student
-> 1) Upload PDF/DOC/PPT
 - Pages -- (no of pages, custom page input)
 - Layout: Portrait/Landscape
 - Color: Black and white/ Color
 - Paper Size: A4,A5
 - Pages per sheet:
 - Margins: No/Low/MEd
 -> Requests

Admin/Replica User:
- Check Requests
- Checks printer availablity
- approves/denies

### Printer Automation
Write program to communicate directly with the printer

### Log Access
Logs the activity of requests and transactions

### Fare Deduction
Show the list of total fare for each user

### File Conversion
Converts file from ppt to pdf, word to pdf

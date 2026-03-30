# oss-audit-24BEC10110

## Student Details

* **Name:** N. Swathi
* **Registration Number:** 24BEC10110
* **Course:** Open Source Software (Linux Administrative)
* **Slot:** F11
* **Date of Submission:** 31 March 2026

---

## Chosen Software

MySQL – Open Source Database Management System (GPL License)

---

## Project Description

This project is an audit of MySQL as part of the Open Source Software course. It combines both theoretical understanding and practical implementation.

The project focuses on the origin and purpose of MySQL, its licensing model, and the ethical ideas behind open-source software. It also explores how MySQL works within a Linux environment and compares it with proprietary database systems.

The practical part of the project is carried out using Linux shell scripts and MySQL queries, showing how open-source tools can be used effectively for automation and data handling.

---

## Scripts Included

Each script was executed in a Linux environment, and its output has been documented in the project report along with screenshots.

### Script 1: System Identity Report

This script displays basic system information such as kernel version, current user, uptime, date, and Linux distribution.

### Script 2: FOSS Package Inspector

This script checks whether MySQL is installed on the system and shows basic package-related information.

### Script 3: Disk and Permission Auditor

This script examines important system directories and displays their permissions and storage usage.

### Script 4: Log File Analyzer

This script reads a log file, counts how many times a keyword such as "error" appears, and displays matching entries.

### Script 5: Open Source Manifesto Generator

This script takes input from the user and generates a short open-source philosophy statement.

---

## SQL Implementation

To support the logic of the shell scripts, a MySQL database was created.

### Database

`oss_project`

### Tables Used

* **logs** – Used for storing and analyzing log messages
* **manifesto_v2** – Used to store user-generated open-source statements

### Operations Performed

* Creating the database and tables
* Inserting sample data
* Querying logs to count error messages
* Retrieving recent log entries
* Storing and displaying manifesto data

---

## How to Run the Project

### Run Shell Scripts

```bash
chmod +x script_name.sh
./script_name.sh
```

### Run SQL Queries

1. Open MySQL Workbench
2. Connect to the MySQL server
3. Execute queries step by step using the Execute button
4. Check the output in the result panel

---

## Requirements

* Linux operating system or terminal environment
* MySQL Server
* MySQL Workbench
* Basic understanding of shell scripting and SQL

---

## Output Documentation

All scripts were executed successfully. The outputs were captured as screenshots and included in the project report.

---

## Conclusion

This project shows how open-source software like MySQL can be used in real-world scenarios. It also demonstrates how Linux tools and database systems can work together for efficient system management and automation.

---

## Acknowledgment

This project was completed as part of the Open Source Software course. It helped in understanding both the theoretical concepts and practical use of open-source technologies.

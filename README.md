# Linux System Health Monitoring and Reporting Tool using Bash

## Overview

The **Linux System Health Monitoring and Reporting Tool** is a Bash scripting project that automates system health checks on a Linux machine. It collects essential system information, generates a structured health report, and saves it as a log file for easy monitoring and troubleshooting.

This project demonstrates practical Linux administration and Bash scripting skills commonly used by system administrators and DevOps engineers.

---

## Features

* Displays disk usage
* Monitors CPU load (1, 5, and 15-minute averages)
* Reports memory and swap usage
* Detects failed systemd services
* Lists the top 5 memory-consuming processes
* Lists the top 5 CPU-consuming processes
* Displays system uptime
* Checks for available package updates (APT, DNF, or YUM)
* Saves the complete report to a log file
* Optional email support for sending reports

---

## Technologies Used

* Bash Shell
* Linux (Ubuntu)
* awk
* systemctl
* ps
* df
* free
* uptime
* apt / dnf / yum

---

## Project Structure

```text
Health-Monitoring-/
├── health.sh
├── README.md
└── screenshots/
    ├── terminal-output.png
    └── report-output.png
```

---

## How It Works

The script performs the following tasks:

1. Collects system information.
2. Checks disk usage.
3. Monitors CPU load.
4. Displays memory and swap usage.
5. Identifies failed services.
6. Finds the top CPU- and memory-consuming processes.
7. Shows system uptime.
8. Checks for available package updates.
9. Generates and saves a detailed system health report.

---

## Installation

Clone the repository:

```bash
git clone git@github.com:psmithun/Health-Monitoring-.git
```

Move into the project directory:

```bash
cd Health-Monitoring-
```

Make the script executable:

```bash
chmod +x health.sh
```

Run the script:

```bash
./health.sh
```

---

## Sample Output

```text
============================================
 System Health Report
============================================

Disk Usage
CPU Load
Memory Usage
Failed Services
Top Memory Processes
Top CPU Processes
System Uptime
Available Package Updates

End of Report
```

The generated report is saved in:

```text
~/system-health-YYYY-MM-DD.log
```

---

## Skills Demonstrated

* Bash Scripting
* Linux System Administration
* Shell Variables
* Conditional Statements (if, elif, else)
* Loops
* Input/Output Redirection
* Process Monitoring
* System Resource Monitoring
* Text Processing using awk
* Git and GitHub Version Control

---

## Future Improvements

* Generate reports in HTML format
* Send email alerts for critical system events
* Schedule automatic execution using Cron
* Monitor network usage
* Monitor disk I/O and CPU temperature
* Export reports in CSV format

---

## Author

**P. S. Mithun**

GitHub: https://github.com/psmithun

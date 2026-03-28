# The Open Source Audit

**A Capstone Project for the Open Source Software (OSS) NGMC Course**

## 👤 Author Information
- **Name:** Daksh Lathiya
- **Registration Number:** 24BCE10371
- **Course:** Open Source Software
- **Slot:** F11

## 📝 Project Overview
Most of the software that powers the modern world was not built by a single company and sold for profit; it was built openly, shared freely, and improved collectively. This project is a comprehensive audit of one such foundational tool: **Git**. 

This project explores Git's origins, the philosophy of its creator, the specific freedoms guaranteed by its GPL license, and its broader impact on the global software ecosystem. In addition to theoretical analysis, this project includes practical Linux footprint mapping and shell scripting tasks that demonstrate how automation and command-line mastery connect directly to the open-source ethos of transparency.

## 🛠️ Shell Scripts Included
This project includes 5 distinct Bash scripts designed to audit, inspect, and automate various Linux system operations.

### 1. `Script1.sh` - System Identity Report
Generates an "Open Source System Identity Report" detailing:
- Student and project information (Chosen Software: Git).
- System information including Kernel Version, Logged-in User, Uptime, and Home Directory.
- Linux Distribution details and Open Source License messaging.

### 2. `Script2.sh` - FOSS Package Inspector
Inspects the installation status of foundational Open Source packages:
- Verifies if a specified package (e.g., Git) is installed via `dpkg`.
- Displays the current version of the software.
- Provides a short philosophical note on the importance of the package (covers Git, Apache, MySQL, Firefox, and VLC).

### 3. `Script3.sh` - Disk and Permission Auditor
Audits critical system directories for security and storage:
- Loops through vital directories (`/etc`, `/var/log`, `/home`, `/usr/bin`, `/tmp`).
- Displays the exact read/write/execute permissions and total disk size of each directory.
- Checks for the existence of the user's `.git` configuration directory.

### 4. `Script4.sh` - Log File Analyzer
A utility to parse and analyze log files for specific events:
- Takes a log file and a keyword (defaults to "error") as arguments.
- Checks if the file exists and is not empty.
- Scans the file line-by-line, counts the occurrences of the keyword, and outputs the last 5 matching lines for quick debugging.

### 5. `Script5.sh` - Open Source Manifesto Generator
An interactive script that promotes the open-source philosophy:
- Prompts the user with three questions regarding their daily open-source tool usage, their definition of freedom, and what they would build and share freely.
- Automatically generates a personalized text file (`manifesto_<username>.txt`) summarizing their open-source beliefs.

## 🚀 How to Run the Scripts

1. **Clone or Download the Repository:**
   Ensure all `.sh` files are in your current directory.

2. **Make the scripts executable:**
   Before running the scripts, you must grant them execution permissions. Open your terminal and run:
   ```bash
   chmod +x Script1.sh Script2.sh Script3.sh Script4.sh Script5.sh# OSS_Project

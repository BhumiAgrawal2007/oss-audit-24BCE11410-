# 🧾 Open Source Audit Report – Mozilla Firefox  

## 👤 Student Details  
- **Name:** Bhumi Agrawal  
- **Roll Number:** 24BCE11410  

---

## 🌐 Selected Software  
**Mozilla Firefox**  

Mozilla Firefox is a widely used open-source web browser maintained by the Mozilla Foundation. It is known for its strong focus on user privacy, security features, and support for open web standards.

---

## 📜 Overview of Scripts  

### 🔹 Script 1: System Information Report  
This script collects and displays key system details such as kernel version, current user, system uptime, date, and Linux distribution information.  

**Concepts used:** variables, command substitution, system commands  

---

### 🔹 Script 2: FOSS Package Checker  
This script checks whether Firefox is installed on the system and shows its version along with additional details.  

**Concepts used:** if-else, dpkg, grep, case statements  

---

### 🔹 Script 3: Disk Usage and Permission Auditor  
This script reviews important system directories for their permissions and disk usage, and also inspects the Firefox configuration directory.  

**Concepts used:** for loop, ls -ld, du, awk, cut  

---

### 🔹 Script 4: Log File Analyzer  
This script reads a log file, counts how many times a given keyword appears, and displays the most recent matching entries.  

**Concepts used:** while loop, if conditions, counters, command-line arguments  

---

### 🔹 Script 5: Open Source Manifesto Creator  
This script generates a personalized open-source manifesto based on user input and saves it into a file.  

**Concepts used:** read, string handling, file redirection, date  

---

## ⚙️ Steps to Execute the Scripts  

### 1️⃣ Open the Linux Terminal (WSL / Ubuntu)  

### 2️⃣ Navigate to the project folder  
cd ~/your-folder-name  

### 3️⃣ Give execution permissions  
chmod +x script1.sh script2.sh script3.sh script4.sh script5.sh  

### 4️⃣ Run the scripts  
bash script1.sh  
bash script2.sh  
bash script3.sh  
bash script4.sh /var/log/syslog error  
bash script5.sh  

---

## 📦 Requirements  
- Bash shell  
- Core Linux utilities (ls, du, grep, awk, cut)  
- Package manager (dpkg for Ubuntu/Debian)  
- Access to system log files  

---

## 📝 Additional Notes  
- Scripts were tested on WSL (Ubuntu)  
- Output may vary depending on system configuration  
- Firefox should be installed for Script 2 to show full details  

---

## ✅ Conclusion  
This project demonstrates practical knowledge of open-source software using Mozilla Firefox. It highlights important Linux concepts, scripting techniques, and the value of open-source ecosystems.
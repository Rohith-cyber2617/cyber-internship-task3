# Cyber Internship - Task 3  
**Vulnerability Scanning on Metasploitable 2 using Acunetix**

## 📌 Objective
The goal of this task is to perform vulnerability scanning on a Metasploitable 2 machine using **Acunetix** and document the findings.

---

## 🛠 Tools Used
- **Acunetix** – Automated web vulnerability scanner  
- **Metasploitable 2** – Intentionally vulnerable Linux VM  

---

## 🔍 Steps Performed
1. Setup **Metasploitable 2** in VMware/VirtualBox.  
2. Verified network connectivity between host and target.  
3. Launched **Acunetix** and configured scan target (Metasploitable 2 IP).  
4. Started the scan and monitored progress.  
5. Captured multiple screenshots during the scan.  

---

## 📷 Screenshots

### 1️⃣ Scan Configuration
![Scan Configuration](screenshots/scan%20configuration.png)

### 2️⃣ Scan Progress
![Scan Process](screenshots/scan%20process2.png)

### 3️⃣ Vulnerabilities Identified (High & Critical)
![High & Critical Vulnerabilities](screenshots/vulnerabilities%20identified%20(High%20&%20critical).png)

### 4️⃣ Medium Vulnerabilities
![Medium Vulnerabilities](screenshots/medium%20vulnerabilities.png)


---

## 📄 Findings & Analysis
See [findings_analysis.md](findings_analysis.md) for a detailed explanation of vulnerabilities and recommendations.

---

## 🏆 Conclusion
Metasploitable 2 contains multiple high-risk vulnerabilities that could be exploited by attackers. Running periodic scans with tools like Acunetix is essential for identifying and mitigating such risks.


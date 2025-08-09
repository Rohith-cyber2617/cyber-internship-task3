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

### 1️⃣ Target Added in Acunetix
![Target Added](screenshots/target_added.png)

### 2️⃣ Scan Progress
![Scan Progress](screenshots/scan_progress.png)

### 3️⃣ Detected Vulnerabilities
![Detected Vulnerabilities](screenshots/vulnerabilities.png)

> **Note:** Place your screenshots inside a `screenshots` folder in your repository before linking.

---

## 📄 Findings & Analysis
See [findings_analysis.md](findings_analysis.md) for a detailed explanation of vulnerabilities and recommendations.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Rohith-cyber2617/cyber-internship-task3.git
   ```
2. Open the screenshots folder to view scan images.  
3. Read the `findings_analysis.md` for detailed analysis.

---

## 🏆 Conclusion
Metasploitable 2 contains multiple high-risk vulnerabilities that could be exploited by attackers. Running periodic scans with tools like Acunetix is essential for identifying and mitigating such risks.


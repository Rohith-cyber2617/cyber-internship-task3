# Findings & Analysis – Cyber Internship Task 3

## Target
- **Machine:** Metasploitable2 VM
- **Purpose:** Web application vulnerability scanning using **Acunetix**

---

## Summary of Findings
During the scan, Acunetix identified multiple vulnerabilities categorized by severity. The scan was stopped midway, so results are **partial**, but they still provide useful security insights.

| Severity | Count | Examples |
|----------|-------|----------|
| High     | X     | SQL Injection, Remote File Inclusion |
| Medium   | X     | Cross-Site Scripting (XSS), Directory Listing |
| Low      | X     | Cookie without Secure Flag, Server Version Disclosure |
| Info     | X     | Missing Security Headers, HTTP Methods Allowed |

> Replace **X** with actual numbers once the report is fully generated.

---

## Key Vulnerabilities Identified

### 1. SQL Injection (High)
- **Impact:** Allows attackers to manipulate database queries, retrieve sensitive data, and potentially gain administrative access.
- **Recommendation:** Use prepared statements and parameterized queries; validate and sanitize inputs.

### 2. Remote File Inclusion (High)
- **Impact:** Can lead to remote code execution by including malicious external files.
- **Recommendation:** Restrict file inclusion to trusted directories; disable `allow_url_include` in PHP.

### 3. Cross-Site Scripting (Medium)
- **Impact:** Attackers can inject malicious scripts into web pages viewed by other users.
- **Recommendation:** Apply output encoding, use Content Security Policy (CSP), sanitize inputs.

### 4. Directory Listing Enabled (Medium)
- **Impact:** Exposes files and directory structure to attackers.
- **Recommendation:** Disable directory listing on the web server.

### 5. Missing Security Headers (Low/Info)
- **Impact:** Reduces protection against attacks such as clickjacking, XSS, and MIME sniffing.
- **Recommendation:** Add headers like `X-Frame-Options`, `Content-Security-Policy`, `Strict-Transport-Security`.

---

## Risk Rating
- The presence of **High severity vulnerabilities** means the target is at **critical risk** if exposed to the internet.
- Exploiting these could lead to **complete system compromise**.

---

## Next Steps
1. **Complete the scan** to obtain full results.
2. Validate findings manually to confirm real vulnerabilities (reduce false positives).
3. Apply security patches and configuration hardening.
4. Re-scan to verify mitigation success.

---

## Notes
- The scan was interrupted before completion. This report will be updated when full results are available.
- Screenshots of detected vulnerabilities are stored in the `screenshots/` directory.

---

**Prepared by:** Rohith (Tony)  
**Date:** *(Add current date here)*  
**Tool Used:** Acunetix

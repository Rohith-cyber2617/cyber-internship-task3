# Methodology - Acunetix Scan on Metasploitable 2

## Step 1: Target Selection
- Target IP: `192.168.50.129`
- Target System: **Metasploitable 2** (intentionally vulnerable Linux VM)
- Scan Tool: **Acunetix**

## Step 2: Scan Configuration
- Scan Type: Full Scan
- Scan Speed: Fast (10 concurrent requests)
- Continuous Scanning: Enabled
- Business Criticality: Critical

## Step 3: Execution
1. Opened Acunetix dashboard.
2. Added target `http://192.168.50.129`.
3. Configured scanning speed & options.
4. Initiated scan and monitored progress.
5. Took screenshots at key points.

## Step 4: Output
- Executive Summary (PDF)
- Affected Items (PDF)
- Screenshots of vulnerabilities.

## Step 5: Next Steps
- Review high severity vulnerabilities.
- Attempt exploitation on isolated lab setup.
- Document remediation strategies.

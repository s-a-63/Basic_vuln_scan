# 📋 Task 3: Basic Vulnerability Scan Using Nessus Essentials

## 🧩 Overview

This repository documents my experience performing a **basic vulnerability scan** on my local PC using **Tenable Nessus Essentials**, as part of a cybersecurity learning task.

The goal was to identify common security vulnerabilities, understand their severity, and document actionable mitigation steps.

---

## 🔧 Tools Used

- **Scanner:** Tenable Nessus Essentials (Free Edition)  
- **Platform:** Windows  
- **Scan Target:** `127.0.0.1` (localhost)  
- **Scan Policy:** Basic Network Scan

---

## ✅ Task Objectives

- Install and configure a free vulnerability scanner (Nessus Essentials).
- Run a full vulnerability scan on the local machine.
- Review the scan report and analyze results.
- Identify and document the most critical vulnerabilities.
- Suggest potential fixes or mitigations.

---

## 📊 Results Summary

| Severity   | Count |
|------------|-------|
| Critical   | 0     |
| High       | 0     |
| Medium     | 2     |
| Low        | 0     |
| Info       | 85    |

**Total Vulnerabilities Detected:** 87

---

## 🔍 Key Findings

- **SSL Self-Signed Certificate**  
  - *Issue:* Non-trusted certificate  
  - *Fix:* Replace with a CA-signed certificate

- **SSL Certificate Cannot Be Trusted**  
  - *Issue:* Certificate not verifiable  
  - *Fix:* Use a certificate from a recognized CA

---

## 📁 Files in this repository
### ▶️  [`Documents/`](./Documents/)
- Screenshots of the scan result
- Task 3-Vulnerability Scan Report : Word document containing the analysis of the scan
- Task3 Scan_Report.html: Exported Nessus vulnerability scan report

---

## 📌 Learning Outcome
This task enhanced my hands-on skills with vulnerability assessment and taught me how to interpret and act on scan reports.




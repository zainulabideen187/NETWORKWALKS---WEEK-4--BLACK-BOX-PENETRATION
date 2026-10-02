# NETWORKWALKS---WEEK-4--BLACK-BOX-PENETRATION# Mediroza General Hospital – Penetration Testing



## 📌 Project Overview

This repository contains the documentation and evidence for a **Black-Box Penetration Testing and Vulnerability Assessment** performed against the Mediroza General Hospital web application.

The project was completed as part of the **Networkwalks B083 – Week 4 Penetration Testing Project**.

**Target:**

`https://medirozahospital.com`

**Client:**

Mediroza General Hospital

**Testing Type:**

Black-Box Penetration Test

**Duration:**

5 Days

---

## 🎯 Project Objectives

The main objectives of this project were:

* Perform reconnaissance against the authorized target.
* Identify exposed application entry points.
* Analyze authentication and application behavior.
* Identify a path to restricted resources.
* Retrieve three confidential patient PDF laboratory reports.
* Analyze the encryption used by the retrieved PDF files.
* Recover the contents of the protected documents.
* Investigate further confidential data exposure.
* Identify employee salary information.
* Identify hospital shareholder information.
* Document findings and remediation recommendations.

---

## 🧪 Assessment Scope

### In Scope

* `https://medirozahospital.com`
* Web application functionality
* Authentication mechanisms
* Application input handling
* Restricted resources
* Authorized document access
* Confidential data exposure

### Out of Scope

* Social engineering
* Denial-of-service attacks
* Systems outside the agreed target
* Unauthorized third-party systems

---

## 🗺️ Project Milestones

### Milestone 1 – Initial Access

The first milestone focused on reconnaissance and identifying exposed entry points in the target application.

The objective was to obtain authorized proof of access and retrieve three confidential patient PDF laboratory reports.

**Evidence:**

```text
evidence/milestone-1/
├── reconnaissance.png
├── entry-point.png
├── restricted-access.png
├── patient-report-1.png
├── patient-report-2.png
└── patient-report-3.png
```

---

### Milestone 2 – Data Extraction

The second milestone focused on analyzing the encryption applied to the three retrieved PDF files.

The objective was to recover the contents of all three files and provide proof of successful access.

**Evidence:**

```text
evidence/milestone-2/
├── pdf-analysis.png
├── recovery-process.png
└── recovered-content.png
```

---

### Milestone 3 – Critical Data Exposure

The third milestone involved analyzing the information obtained during the previous stages and identifying further confidential information exposed by the client server.

The investigation focused on:

* Employee salary information
* Hospital shareholder details

**Evidence:**

```text
evidence/milestone-3/
├── data-exposure.png
├── employee-data.png
└── shareholder-data.png
```

---

### Milestone 4 – Penetration Testing Report

The final milestone was the preparation of a professional penetration testing report.

The report contains:

* Executive Summary
* Scope and Methodology
* Findings
* Proof of Exploitation
* Risk Ratings
* Recommendations
* Remediation Guidance
* Conclusion

---

## 🔍 Methodology

The assessment followed a structured black-box testing methodology:

```text
Reconnaissance
      ↓
Attack Surface Identification
      ↓
Authentication Analysis
      ↓
Application Testing
      ↓
Restricted Resource Access
      ↓
Document Analysis
      ↓
Data Exposure Investigation
      ↓
Risk Assessment
      ↓
Reporting & Remediation
```

---

## 🛠️ Tools

Tools used during the assessment should be documented below according to the actual tools used:

* Web Browser
* Burp Suite
* Nmap
* PDF analysis tools
* Password recovery tools
* Wordlists
* Linux command-line utilities
* Screenshot/evidence tools

> Only include tools that were actually used during the assessment.

---

## 📂 Repository Structure

```text
mediroza-pentest/
│
├── README.md
│
├── report/
│   └── Mediroza_Penetration_Testing_Report.pdf
│
├── evidence/
│   │
│   ├── milestone-1/
│   │   ├── reconnaissance.png
│   │   ├── entry-point.png
│   │   └── restricted-access.png
│   │
│   ├── milestone-2/
│   │   ├── pdf-analysis.png
│   │   └── recovery-proof.png
│   │
│   └── milestone-3/
│       ├── data-exposure.png
│       └── server-exposure.png
│
└── notes/
    └── methodology.md
```

---

## 📊 Findings

The final repository should document only findings that were actually confirmed during the assessment.

| ID   | Finding                                 | Status       |
| ---- | -------------------------------------- | -------- | ------------ |
| F-01 | Restricted resource access weakness    | Open |
| F-02 | Confidential patient document exposure | Open |
| F-03 | Weak document protection               | Open |
| F-04 | Employee salary data exposure          | Open |
| F-05 | Shareholder information exposure       |  Open |

---

## 🛡️ Recommended Remediation

General remediation recommendations include:

### Authentication & Authorization

* Implement strong authentication.
* Apply server-side authorization checks.
* Use role-based access control.
* Follow the principle of least privilege.
* Prevent unauthorized direct access to restricted resources.

### Sensitive Documents

* Store confidential documents securely.
* Prevent public access to patient reports.
* Use unpredictable file references.
* Validate authorization before document downloads.
* Monitor sensitive file access.

### Encryption

* Use strong document encryption.
* Avoid predictable passwords.
* Use unique credentials for sensitive documents.
* Secure encryption keys.

### Sensitive Data

* Restrict employee salary information.
* Restrict shareholder information.
* Encrypt sensitive information.
* Monitor access to confidential records.
* Perform regular security reviews.

---

## 📸 Evidence

Screenshots and supporting evidence should be stored in the `evidence/` directory.

Before uploading evidence to a public GitHub repository:

* Remove passwords.
* Redact patient information.
* Redact employee personal information.
* Redact financial information.
* Redact sensitive shareholder information.
* Remove session cookies and authentication tokens.
* Remove API keys and other secrets.

---

## 📄 Report

The complete penetration testing report is available in:

```text
report/Mediroza_Penetration_Testing_Report.pdf
```

---

## ⚠️ Disclaimer

This project was conducted in a **controlled and authorized educational environment**.

The target was provided for authorized security testing, and the project documentation states that written permission was granted.

This repository is intended for:

* Educational purposes
* Cybersecurity learning
* Penetration testing documentation
* Security research in authorized environments

Do not use the techniques documented in this repository against systems without explicit written authorization.

---

## 👨‍💻 Author

**Zain Ul Abideen**

Cyber Security Student

**Project:** Mediroza General Hospital Penetration Testing
**Batch:** B083 – Week 4

---

## ⭐ Project Learning Outcomes

Through this project, the following cybersecurity skills were practiced:

* Web reconnaissance
* Attack-surface identification
* Authentication analysis
* Web application testing
* Access-control testing
* Document security analysis
* Encryption analysis
* Sensitive-data exposure analysis
* Vulnerability documentation
* Risk assessment
* Security remediation
* Professional penetration testing reporting

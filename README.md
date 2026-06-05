# GRC Portfolio: Governance, Risk, and Compliance Baseline Project

Welcome to my Governance, Risk, and Compliance (GRC) portfolio project. This repository demonstrates foundational, practical skills required of a GRC Analyst. It covers asset lifecycle management, quantitative risk assessment modeling using international standards, and corporate policy architecture.

All tasks are modeled around a fictional digital health entity, **Alpha HealthTech Solutions**, a telemedicine company handling sensitive data subject to strict **HIPAA** and **GDPR** regulations.

---

## 📂 Project Structure

This portfolio contains three distinct execution modules:
1. **Task 1:** Enterprise Micro-Asset Inventory (15 Assets)
2. **Task 2:** ISO 31000-Style Dual-Scenario Risk Register
3. **Task 3:** Corporate AI Acceptable Use Policy (AUP)

---

## 🛠️ Task 1: Micro-Asset Inventory (The Absolute Baseline)

**Objective:** Establish operational visibility. In GRC, you cannot protect or audit what you do not know exists.  
**Execution:** A granular, 15-asset inventory segregating infrastructure, endpoint devices, and software systems. It maps accountability and data classifications to prevent data leakage and unauthorized access.

### Asset Matrix Snippet

| Asset ID | Asset Name / Type | Data Classification | Business Owner | Technical Owner | Skill Gained
| :--- | :--- | :--- | :--- | :--- |
| **AST-01** | Production Database Server (AWS RDS) | Confidential | VP of Operations | Lead DevOps Engineer |
| **AST-02** | Corporate Laptops (MacBook Pro) | Confidential | HR Director | IT Support Manager |
| **AST-07** | Patient Portal Web Application | Confidential | Chief Product Officer | Lead Software Engineer |
| **AST-13** | Identity & Access Management (Okta) | Confidential | CISO | IAM Engineer |

> *The full 15-asset catalog is available 

---

## 📊 Task 2: Risk Assessment & Matrix (ISO 31000 Framework)

**Objective:** Identify operational vulnerabilities, quantify business impact, and map technical treatments to preserve enterprise integrity.  
**Formula Applied:** $\text{Risk Score} = \text{Likelihood (1–5)} \times \text{Impact (1–5)}$

### Risk Register Entries

#### 🚨 Scenario A: Data Leakage via Public AI Tiers
* **The Threat:** Employees using free versions of ChatGPT to write corporate emails and summarize internal documentation. Free-tier tools retain user text inputs for public model training.
* **The Consequence:** Proprietary source code and protected health information (PHI) leak publicly, triggering catastrophic regulatory fines and brand degradation.
* **Risk Score:** Likelihood (4) $\times$ Impact (4) = **16 (Critical Risk)**
* **The Treatment Plan:** Enforce domain-level blocks on public AI tools via corporate firewalls. Provision enterprise-licensed AI accounts covered by explicit Data Processing Agreements (DPAs).
* **Treatment Owner:** Chief Information Security Officer (CISO)

#### 🚨 Scenario B: Algorithmic Hallucination & Medical Malpractice
* **The Threat:** Clinicians utilizing unauthorized generative AI models to summarize complex patient histories and draft clinical clinical letters without strict verification gates.
* **The Consequence:** The AI model hallucinates incorrect patient information, leading to faulty medical advice, severe patient harm, and multi-million dollar malpractice lawsuits.
* **Risk Score:** Likelihood (3) $\times$ Impact (5) = **15 (Critical Risk)**
* **The Treatment Plan:** Deploy an FDA-compliant, clinically validated AI summarization tool that mandates source-record citations. Enforce documented "human-in-the-loop" verification protocols.
* **Treatment Owner:** Chief Medical Officer (CMO)

*Skills Gained: Risk Taxonomy, Risk Register Maintenance, and Healthcare Compliance Alignment.*

---

## 📜 Task 3: AI Acceptable Use Policy (AUP)

**Objective:** Draft organizational "laws" that govern employee behavior regarding emerging technologies.  
**Execution:** A complete, 1-page corporate policy mapping approved digital environments, explicit data boundaries, and strict compliance enforcement rules.

### Document Specifications
* **Document ID:** POL-2026-AI-01
* **Compliance Overlap:** HIPAA § 164.308 (Administrative Safeguards), GDPR Article 32 (Security of Processing)

### Key Clauses Structured Within Policy:
* **Purpose:** Outlines the operational risks AI poses to data privacy and regulatory alignment.
* **Approved Whitelist:** Restricts company data processing exclusively to enterprise-authenticated instances of Microsoft Copilot and Claude on managed browsers.
* **Prohibited Actions:** Enforces zero-tolerance boundaries against pasting proprietary source code, patient PII, or internal health metadata into unauthorized environments.

> *The full markdown text for this policy can be reviewed

---

## 🧠 Key GRC Competencies Demonstrated
* **Regulatory Knowledge:** Deep alignment with global security frameworks (HIPAA and GDPR data protection mandates).
* **Risk Management Foundations:** Practical implementation of quantitative matrix methodologies following ISO 31000 principles.
* **Technical Writing:** Ability to translate complex infrastructure landscapes and high-level technical vectors into simple corporate policy language.

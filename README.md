# 🆔 OAlias

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%20%2F%20Windows-informational?style=flat-square&logo=linux&logoColor=white&color=0a0c10"/>
  <img src="https://img.shields.io/badge/Category-ORec%20%2F%20Social%20Engineering-cyan?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dependencies-faker-yellow?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-v1.0-cyan?style=flat-square"/>
</p>

> **OAlias** is a realistic fake identity generator designed for authorised penetration testing, security awareness training, and test data creation. It supports 12 locales, multiple data profiles, bulk generation, and exports to TXT, JSON, and CSV.

**Perfect for red team operations, phishing simulations, and secure test environments.**

---

## 📌 Overview

OAlias generates high-quality synthetic identities with realistic names, contact details, addresses, professional information, online profiles, financial data, and identity documents — all while maintaining cultural accuracy through locale support.

It includes predefined profiles (Basic, Full, Online, Corporate, Financial, Document) and a custom field selector for maximum flexibility.

---

## 🖥️ Modules

| # | Module                | Description |
|---|-----------------------|-------------|
| **[1]** | **Generate**          | Full generation with locale, profile, count, and export |
| **[2]** | **Quick Identity**    | Generate and display one complete identity instantly |
| **[3]** | **Bulk Export**       | Generate 100–10,000 identities silently and export directly |
| **[4]** | **Field Browser**     | Browse all 35 available fields and profiles |

---

## 📊 Key Features

- **12 Locales** — English (US/UK), Arabic (Egypt/Saudi), French, German, Spanish, Italian, Japanese, Chinese, Russian, Portuguese (BR)
- **35+ Data Fields** — Name, email, phone, address, DOB, job, company, username, password, IP, MAC, credit card, passport, SSN, and more
- **6 Predefined Profiles** + Custom selection
- **Bulk Generation** — Up to 10,000 identities with progress bar
- **Multiple Export Formats** — TXT (human-readable), JSON (structured), CSV (spreadsheet-ready)
- **Clean Terminal UI** — Professional colored output with clear sections
- **Report Directory** — All exports saved to `oalias_reports/`

---

## ⚙️ Requirements

- **faker**:
  ```bash
  pip install faker
  chmod +x OAlias
  ./OAlias

  Choose [1] Generate
Select locale (default: English US)
Choose data profile (Basic, Full, Online, Corporate, Financial, Document, or Custom)
Enter number of identities (1–500 recommended)
Choose export format (TXT / JSON / CSV / All)
Identities are generated and saved automatically

Quick Mode [2] — Instantly generates and displays one full identity.
Bulk Mode [3] — Silent high-volume generation for large test datasets.

📁 Output

Live Terminal — Real-time generation with colored identity display
Reports (saved in oalias_reports/):
oalias_YYYYMMDD_HHMMSS.txt — Human-readable report
oalias_YYYYMMDD_HHMMSS.json — Structured data
oalias_YYYYMMDD_HHMMSS.csv — Spreadsheet format



📦 Part of OwlSec Toolkit
This tool is part of the OwlSec suite — a collection of 300+ security and privacy tools.
🔗 owlsec.org

©️ License
Proprietary — © Khaled S. Haddad
Tools are distributed as pre-built executables. Source code is proprietary.
AUTHORISED SECURITY TESTING, SOCIAL ENGINEERING SIMULATION & TEST DATA GENERATION ONLY
  

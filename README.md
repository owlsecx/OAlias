# 🦉 OAlias

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OReconnaissance-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-2.1-cyan?style=flat-square"/>
</p>

> **OAlias** — Advanced Fake Identity Generator

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OAlias is an advanced fake-identity generator for authorised penetration testing, security-awareness training, red-team operations, QA test-data seeding and OSINT simulation. It produces highly realistic synthetic profiles across 20+ locales, with reproducible output when a seed is supplied so test data can be regenerated exactly. Identities can be exported in bulk to TXT, JSON, CSV, XML, YAML or SQL for downstream use.

---

## ✨ Features

- Realistic fake identities across 20+ locales
- Reproducible generation via --seed (same seed, locale and fields → same data)
- Bulk generation of many identities with a single command
- Custom profiles and selectable field sets
- Export to JSON, CSV, XML, YAML, SQL and TXT
- Field and locale discovery with --list-fields / --list-locales

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OAlias --quick
./OAlias --bulk 100 --locale en_US --fmt csv
./OAlias --list-locales
./OAlias --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*

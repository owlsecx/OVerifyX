# 🦉 OVerifyX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OForensics-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0-cyan?style=flat-square"/>
</p>

> **OVerifyX** — Professional File Integrity Suite

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview


OVerifyX is a file-integrity and verification tool that computes and compares cryptographic hashes to detect tampering. It supports multiple hash algorithms, baseline manifests and recursive directory verification, reporting added, removed and modified files. It is intended for authorized integrity monitoring and forensic validation.

---

## ✨ Features


- Multi-algorithm hashing (SHA-256 and other hashlib digests) of files and directories
- Baseline manifest creation and later verification against it
- Recursive directory walking with added / removed / modified detection
- Clear tamper reporting with per-file status
- Structured export of verification results
- Offline --self-test for safe verification

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage


```bash
./OVerifyX
./OVerifyX --self-test
./OVerifyX --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 275+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

Proprietary — © 2026 Owlsec LLC. All rights reserved.

*Tools are distributed as pre-built executables. Source code is proprietary.*

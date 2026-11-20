# 🛡️ Cybersecurity & Ethical Hacking Internship — Week 3

Welcome to my **Week 3** repository for the Cybersecurity & Ethical Hacking Internship at **Networkwalks Academy**, mentored by **Waqas Karim** sir.

This week covers cryptographic hash extraction, local dictionary-based password auditing, browser-based hash utilities, and AI-assisted penetration testing workflows using the **Hexstrike Model Context Protocol (MCP)** server with Claude Desktop.

---

## 📂 Repository Structure

```text
Cybersecurity-Internship-Week3/
├── module 1/                  # Password Cracking with John the Ripper & Johnny GUI
│   ├── screnshots pdf 1/      # Execution & flag capture screenshots (PDF 1)
│   ├── screenshots pdf 2/     # Execution & hash cracking proofs (PDF 2)
│   ├── screenshots pdf 3/     # Execution & hash cracking proofs (PDF 3)
│   ├── hash1.txt              # Extracted $pdf$ hash for PDF 1
│   ├── hash2.txt              # Extracted $pdf$ hash for PDF 2
│   └── hash3.txt              # Extracted $pdf$ hash for PDF 3
├── module 2/                  # Browser-Based Hash Calculation & Password Cracker
│   └── *.png                  # Web utility hash generation & cracking screenshots
├── lab practice/              # Hexstrike MCP Server Setup & Integration
│   └── *.jpeg                 # Kali Linux API server & Claude Desktop configuration proofs
└── optional module lab/       # AI-Assisted Password Auditing with Hexstrike MCP
    └── *.jpeg                 # Automated AI-driven hash cracking workflow proofs
```

---

## 🛠️ Modules & Lab Breakdown

### 🔹 Module 1: Password Cracking with John the Ripper & Johnny GUI
Performed local cryptographic hash extraction and dictionary-based password auditing against three encrypted PDF files.
* **Hash Extraction:** Extracted crackable `$pdf$` hashes (`hash1.txt`, `hash2.txt`, `hash3.txt`) using `pdf2john`.
* **Toolchain Execution:** Configured **John the Ripper (JTR)** alongside the **Johnny GUI** frontend wrapper on Kali Linux to run automated dictionary attacks.
* **Key Result:** Successfully recovered the target password (`good-luck`) and captured the verification flag: `nw{cybersecurity_flag_captured_2608}`.

### 🔹 Module 2: Browser-Based Hash Calculation & Password Cracker
Explored lightweight, browser-based cryptographic tools for rapid password auditing without local toolchain installation.
* **Hash Generation & Auditing:** Used the **Networkwalks Hash Calculator** and **Password Cracker** utilities to generate hashes and test password resilience against standard wordlists.

### 🔹 Lab Practice: Hexstrike MCP Server Setup
Built and integrated an AI-assisted offensive security environment on Kali Linux.
* **Server Deployment:** Cloned `hexstrike-ai`, set up an isolated Python virtual environment (`hexstrike-env`), installed dependencies, and launched the local Flask API server on `http://localhost:8888`.
* **Claude Desktop Integration:** Configured `claude_desktop_config.json` to connect Claude Desktop with the local Hexstrike MCP server.

### 🔹 Optional Module Lab: AI-Assisted Password Auditing
Utilized the integrated **Hexstrike MCP + Claude Desktop** setup to automate hash inspection and John the Ripper password cracking workflows through natural language prompts.

---

## 🙏 Acknowledgement
Special thanks to my mentor **Waqas Karim** sir and **Networkwalks Academy** for designing practical, hands-on cybersecurity labs that bridge theoretical concepts with real-world offensive security tools.

---

## 👤 Author
* **Name:** Vanshita Choudhary
* **Institution:** Acropolis Institute of Technology & Research, Indore
* **Batch:** BT804C
* **GitHub:** [@vanshitachoudhary](https://github.com/vanshitachoudhary)

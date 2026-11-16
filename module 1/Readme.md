# 🛡️ Cybersecurity Internship - Week 3: Project Module 1 (Password Cracking with JTR & Johnny GUI)

Welcome to the repository for **Week 3 - Module 1** of the Cybersecurity & Ethical Hacking Internship with **Networkwalks** (Batch: BT804C)[cite: 5]. This module focuses on cryptographic hash extraction, password auditing, and executing dictionary-based attacks using John the Ripper and Johnny GUI[cite: 5, 9].

---

## 📋 Table of Contents
- [Objective](#-objective)
- [Tools Used](#-tools-used)
- [Step-by-Step Implementation Workflow](#-step-by-step-implementation-workflow)
- [Results & Captured Flag](#-results--captured-flag)

---

## 🎯 Objective
The primary objective of this module is to recover the document-open password of a password-protected PDF file (`My Locked PDF1.pdf`) on a Windows PC using CLI-based **John the Ripper (JTR)** and GUI-based **Johnny**[cite: 5, 9].

---

## 🛠️ Tools Used
* **OnlineHashCrack (PDF Hash Extractor):** Used to extract the crackable `$pdf$` hash format from the encrypted PDF file[cite: 13, 14].
* **John the Ripper (JTR Jumbo):** CLI-based password recovery and auditing utility[cite: 6, 9].
* **Johnny GUI:** Graphical point-and-click user interface wrapper for John the Ripper[cite: 5].
* **Adobe Acrobat Reader:** Used to open the encrypted PDF using the cracked password and retrieve the verification flag[cite: 19, 21].

---

## 🚀 Step-by-Step Implementation Workflow
1. **Hash Extraction:** Uploaded the encrypted target file (`My Locked PDF1.pdf`) to an authorized online extractor to derive the compatible password hash starting with `$pdf$`[cite: 13, 14].
2. **File Preparation:** Copied the extracted hash string and saved it locally into a text file named `hash1.txt`[cite: 14, 16].
3. **Tool Configuration:** Linked the Johnny GUI interface with the core JTR executable (`john.exe`) in the JTR binary run directory[cite: 11, 12].
4. **Dictionary Attack Execution:** Imported `hash1.txt` into Johnny as a password file and launched a structured dictionary attack using built-in wordlists[cite: 17, 18, 19].
5. **Credential Recovery:** Successfully processed the hashes and recovered the plaintext password (`good-luck`)[cite: 31].

---

## 🚩 Results & Captured Flag
* **Cracked Password:** `good-luck`[cite: 31]
* **Captured Flag:** `nw{cybersecurity_flag_captured_2608}`[cite: 32]
* **Verification:** Unlocked the secure PDF successfully and verified system integrity[cite: 21, 32].

---

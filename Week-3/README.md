# Week 3: Password Auditing & Hash Cracking (John the Ripper & NW Tools)

## Overview
This document logs my Week 3 password recovery and cryptographic auditing labs for the **Networkwalks Cybersecurity Internship (Batch B084)**, demonstrating offline dictionary attacks with John the Ripper (`JTR`) in Kali Linux and online hash recovery using Networkwalks security utilities.

## Scope & Target Information
- **Target File:** `My-Locked-PDF1.pdf` (Authorized Training Lab File)
- **Tools Used:** `pdf2john`, `John the Ripper (JTR)`, `rockyou.txt` wordlist, Networkwalks Hash Calculator, Networkwalks Password Cracker

## Summary of Activities
1. **Hash Extraction (`pdf2john`):** Extracted the cryptographic PDF password hash (`$pdf$...`) from `My-Locked-PDF1.pdf` in Kali Linux.
2. **Offline Dictionary Attack (`John the Ripper`):** Cracked the extracted hash using the `rockyou.txt` wordlist (`john --wordlist=...`) and verified the recovered plaintext password via `john --show`.
3. **Document Decryption Verification:** Opened the protected PDF using the recovered password to verify full file access.
4. **Online Hash Generation & Cracking:** Replicated hash extraction and password recovery using the Networkwalks Hash Calculator and Networkwalks Password Cracker web tools.

## Screenshots

### 0. /home/kali/Downloads Location where the file is kept
![/home/kali/Downloads Location where the file is kept](.0-kali-home-dir.png)

### 1. PDF Hash Extraction (`pdf2john`)
![PDF Hash Extraction](./01-pdf-hash.png)

### 2. Password Cracking with John the Ripper
![John the Ripper Crack](./02-jtr-cracked.png)

### 3.1. Unlocked PDF Verification/Enter the found password
![Unlocked PDF](./03-unlocked-pdf1.png)

### 3.2. Unlocked PDF Data/Flag shown
![Unlocked PDF](./03-unlocked-pdf2.png)

### 4. Networkwalks Hash Calculator
![NW Hash Calculator](./04-nw-hash.png)

### 5. Networkwalks Online Password Cracker
![NW Password Cracker](./05-nw-cracked.png)

## Author
- **Name:** Jai Bhushan Rane | **Intern ID:** NW-084-3I7 | **Batch:** B084

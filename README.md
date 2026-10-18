# Cyrptix CTF — OSINT & Forensics Write-Ups

<div align="center">

![CTF](https://img.shields.io/badge/CTF-Cyrptix%20%2F%20Cytech-orange?style=for-the-badge)
![Category](https://img.shields.io/badge/Track-OSINT%20%26%20Digital%20Forensics-blue?style=for-the-badge&logo=target)
![Progress](https://img.shields.io/badge/Challenges%20Solved-5%20%2F%205-success?style=for-the-badge&logo=checkmarx)
![Author](https://img.shields.io/badge/Author-Dabuynyx-purple?style=for-the-badge&logo=github)

</div>

---

## 📖 Overview

This repository / folder contains the complete, detailed write-ups and forensic artifacts for the 5 OSINT & Git Forensics challenges from the **Cyrptix CTF**.

Each challenge directory includes full step-by-step methodology, reproducible terminal commands (`git`, `openssl`, `exiftool`, `base64`, `python3`), visual investigation flowcharts, raw challenge artifacts, and primary intelligence sources.

---

## 🎯 Challenges Summary & Index

| # | Challenge Name | Category | Solved Flag | Write-Up Folder |
| :-: | :--- | :--- | :--- | :--- |
| **1** | **The Ghost in the Blocks** | OSINT / Git Forensics | `CTF{cryptix}` | [📂 1. The Ghost in the Blocks](./1.%20The%20Ghost%20in%20the%20Blocks/README.md) |
| **2** | **Bangladesh Bank Cyber Heist** | OSINT / Threat Intelligence | `Cryptix{fandation_Jupiter_ChosunExpoJointVenture_90}` | [📂 2. Bangladesh Bank Cyber Heist](./2.%20Bangladesh%20Bank%20Cyber%20Heist/README.md) |
| **3** | **Old Friends** | OSINT / Web Archive / EXIF | `Cryptix{stonehenge}` | [📂 3. Old Friends](./3.%20Old%20Friends/README.md) |
| **4** | **Behind the Shroud** | OSINT / Threat Intelligence | `Cryptix{OperationShroudedHorizon_12_M1rr0r}` | [📂 4. Behind the Shroud](./4.%20Behind%20the%20Shroud/README.md) |
| **5** | **Ghost in the Release** | Git Forensics / Crypto / OSINT | `Cryptix{v4ult_unl0ck3d_st4g3_tw0_n0t3s_0s1nt_g1st_w1ns}` | [📂 5. Ghost in the Release](./5.%20Ghost%20in%20the%20Release/README.md) |

---

## 📁 Repository Structure

```text
Cyrptix CTF OSINT write up/
├── README.md                                  # Master index and summary
├── 1. The Ghost in the Blocks/
│   └── README.md                              # Commit digging & Base64 decoding
├── 2. Bangladesh Bank Cyber Heist/
│   └── README.md                              # 4-Part DOJ & SWIFT heist investigation
├── 3. Old Friends/
│   ├── README.md                              # Web archive timeline & GPS forensics
│   ├── deleted_post.html                      # Challenge web snapshots
│   └── image_4_0_next_build_a_11_replica.jpg  # Extracted reference image with EXIF
├── 4. Behind the Shroud/
│   └── README.md                              # Darkode takedown & Daniel Placek aliases
└── 5. Ghost in the Release/
    ├── README.md                              # Git plumbing, OpenSSL AES decryption & Gists
    └── payguard-vault.tar.gz                  # Challenge Git repository archive
```

---

## 🛠️ Tools & Technologies Used

* **Git Forensics:** `git log -p`, `git for-each-ref`, `git notes`, `git fsck`, `git show`
* **Cryptography & Encoding:** `base64`, `openssl enc` (PBKDF2, AES-256-CBC, SHA-256)
* **Image & Metadata Forensics:** `exiftool`, coordinate DMS $\to$ Decimal conversion
* **OSINT & Intelligence Gathering:** Google dorking, GitHub Gist OSINT, CourtListener court dockets, FBI & DOJ official disclosures

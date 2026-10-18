# Cyrptix CTF — OSINT & Digital Forensics Write-Ups

<div align="center">

![CTF](https://img.shields.io/badge/CTF-Cyrptix%20%2F%20Cytech-orange?style=for-the-badge)
![Track](https://img.shields.io/badge/Track-OSINT%20%26%20Digital%20Forensics-blue?style=for-the-badge&logo=target)
![Progress](https://img.shields.io/badge/Challenges%20Solved-5%20%2F%205-success?style=for-the-badge&logo=checkmarx)
![Author](https://img.shields.io/badge/Author-Dabuynyx-purple?style=for-the-badge&logo=github)

A comprehensive, production-grade collection of write-ups, digital forensic artifacts, and reproducible methodologies for the **Cyrptix CTF** OSINT and Git Forensics challenges.

</div>

---

## 📖 Overview

This repository documents the end-to-end investigation, reverse engineering, and threat intelligence workflows used to solve all 5 OSINT and Digital Forensics challenges in the **Cyrptix CTF**.

Every challenge contains:
- 📌 **Incident Scenario & Narrative:** Detailed threat context, actor profiles, and intelligence background.
- 🗺️ **Visual Investigation Flowcharts:** Step-by-step Mermaid diagrams mapping out the investigative pivots.
- 💻 **Complete CLI Reproduction Commands:** Copy-pasteable commands across `git`, `openssl`, `exiftool`, `curl`, and `python3`.
- 📁 **Challenge Artifacts:** Recovered disk images, web archives, encrypted vaults, and metadata files.
- 📚 **Primary Intelligence Disclosures:** References to official DOJ indictments, FBI cyber bulletins, and news records.

---

## 🎯 Challenges Summary & Navigation

| # | Challenge Name | Primary Categories | Final Flag | Challenge Folder | Standalone Repository |
| :-: | :--- | :--- | :--- | :-: | :-: |
| **1** | **The Ghost in the Blocks** | OSINT • Git Forensics | `CTF{cryptix}` | [📂 Read Write-Up](./1.%20The%20Ghost%20in%20the%20Blocks/README.md) | [🔗 Standalone Repo](https://github.com/Dabuynyx/osint-writeup-cytech-the-ghost-in-the-blocks) |
| **2** | **Bangladesh Bank Cyber Heist** | Threat Intelligence • OSINT | `Cryptix{fandation_Jupiter_ChosunExpoJointVenture_90}` | [📂 Read Write-Up](./2.%20Bangladesh%20Bank%20Cyber%20Heist/README.md) | [🔗 Standalone Repo](https://github.com/Dabuynyx/osint-writeup-cytech-bangladesh-bank-cyber-heist) |
| **3** | **Old Friends** | Web Archive Forensics • Geolocation | `Cryptix{stonehenge}` | [📂 Read Write-Up](./3.%20Old%20Friends/README.md) | [🔗 Standalone Repo](https://github.com/Dabuynyx/osint-writeup-cytech-old-friends) |
| **4** | **Behind the Shroud** | Threat Intelligence • OSINT | `Cryptix{OperationShroudedHorizon_12_M1rr0r}` | [📂 Read Write-Up](./4.%20Behind%20the%20Shroud/README.md) | [🔗 Standalone Repo](https://github.com/Dabuynyx/osint-writeup-cytech-behind-the-shroud) |
| **5** | **Ghost in the Release** | Git Plumbing • PBKDF2/AES • OSINT | `Cryptix{v4ult_unl0ck3d_st4g3_tw0_n0t3s_0s1nt_g1st_w1ns}` | [📂 Read Write-Up](./5.%20Ghost%20in%20the%20Release/README.md) | [🔗 Standalone Repo](https://github.com/Dabuynyx/osint-writeup-cytech-ghost-in-the-release) |

---

## 📁 Repository Structure

```text
Cyrptix CTF OSINT write up/
├── README.md                                  # Master index and challenge overview
├── 1. The Ghost in the Blocks/
│   └── README.md                              # Commit digging & Base64 decoding
├── 2. Bangladesh Bank Cyber Heist/
│   └── README.md                              # 4-Question SWIFT heist & DOJ docket investigation
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

## 🛠️ Required Tools & Dependencies

All solutions use standard open-source tools:

```bash
# MacOS (via Homebrew)
brew install git exiftool openssl python3 curl

# Debian / Ubuntu
sudo apt-get update && sudo apt-get install -y git libimage-exiftool-perl openssl python3 curl
```

---

## ⚖️ Disclaimer

All materials, intelligence disclosures, and technical methodologies documented in this repository are for educational, CTF research, and authorized digital forensics training purposes only.

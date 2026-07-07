# Active Directory Home Lab - Part 1: Environment Setup

> **Project Series:** Building a Complete Active Directory Home Lab

## Overview

This repository documents the initial setup of an Active Directory home lab using **Windows Server 2022** and **Windows 10 Enterprise** virtual machines.

This is **Part 1** of a larger series and focuses solely on preparing the lab environment.

---

## Lab Components

- Windows Server 2022 (Domain Controller)
- Windows 10 Enterprise Client 01
- Windows 10 Enterprise Client 02
- VMware Workstation
- Internal Virtual Network

---

## Project Roadmap

- ✅ Part 1 – Active Directory Lab Setup *(Current Repository)*
- ⏳ Part 2 – Joining Windows Clients to the Domain
- ⏳ Part 3 – Active Directory Administration
- ⏳ Part 4 – Group Policy
- ⏳ Part 5 – Offensive Security Lab
- ⏳ Part 6 – Detection & Defense

---

## Repository Structure

```text
.
├── README.md
├── screenshots/
└── assets/
```

---

## Contents

- Lab Overview
- Architecture
- Prerequisites
- Virtual Machine Setup
- Windows Server Installation
- Active Directory Installation
- Domain Configuration
- Windows 10 Preparation
- Networking
- Validation
- Troubleshooting
- References

> Detailed documentation and screenshots will be added in future updates.

---

## Lab Architecture

```text
                 Internet
                     │
              Host Machine
                     │
         VMware Internal Network
          ┌──────────┴──────────┐
          │                     │
 Windows Server 2022      Windows 10 Clients
 Domain Controller      Client01 / Client02
```

---

## Current Status

- Repository initialized
- Initial documentation created
- Screenshots pending organization
- Detailed walkthrough coming soon

---

## Future Improvements

- Detailed installation guide
- Configuration screenshots
- PowerShell commands
- Network diagrams
- Troubleshooting notes
- Pentester observations
- Security best practices

---

## Disclaimer

This project is intended for educational purposes within an isolated home lab environment.

# WestWild-CTF-Machine
# WestWild Capture The Flag (CTF) Machine Development

## Project Overview

This repository presents the design, deployment, and customization of the **WestWild Capture The Flag (CTF)** machine within a virtual cybersecurity laboratory. The project was completed using **Kali Linux** as the attacking machine and **Ubuntu 14.04.6 LTS** as the target machine hosted on **VMware Workstation 17 Pro**.

The project demonstrates the complete penetration testing lifecycle, including network reconnaissance, service enumeration, SMB share analysis, credential extraction, SSH authentication, privilege escalation, flag retrieval, Apache web server configuration, website customization, Linux user management, hostname modification, and creation of custom CTF flags.

---

## Project Information

**Project Title:** WestWild Capture The Flag (CTF) Machine Development

**Target Machine:** WestWild

**Attacker Machine:** Kali Linux

**Target Operating System:** Ubuntu 14.04.6 LTS

**Virtualization Platform:** VMware Workstation 17 Pro

---

## Objectives

* Build and customize a Linux-based CTF environment.
* Perform host discovery and network reconnaissance.
* Enumerate running network services.
* Access and analyze SMB shares.
* Extract and decode hidden credentials.
* Obtain SSH access to the target system.
* Perform Linux privilege escalation.
* Capture user and root flags.
* Configure the Apache web server.
* Deploy a customized portfolio webpage.
* Create and manage Linux users.
* Modify the system hostname.
* Design and implement custom CTF flags.

---

## Technologies and Tools

* VMware Workstation 17 Pro
* Kali Linux
* Ubuntu 14.04.6 LTS
* Netdiscover
* Nmap
* SMBClient
* SSH
* Base64
* Find
* Apache2
* Nano
* useradd
* passwd
* usermod
* hostnamectl

---

## Repository Structure

```text
WestWild-CTF-Machine/
│
├── README.md
├── WestWild_CTF_Report.pdf
├── Website/
│   ├── index.html
│   ├── style.css
│   └── assets/
├── Screenshots/
├── Virtual_Machine/
│   ├── WestWild.ovf
│   ├── WestWild.mf
│   └── WestWild-disk1.vmdk
└── Documentation/
```

---

## Target Machine Configuration

### Target System

* Ubuntu 14.04.6 LTS
* Apache2 Web Server
* OpenSSH Server
* Samba Service

### Attacker System

* Kali Linux
* VMware NAT Network

---

## Project Highlights

* Network Host Discovery
* TCP Port Scanning
* Service Enumeration
* SMB Share Enumeration
* File Retrieval from SMB
* Credential Discovery
* Base64 Credential Decoding
* SSH Remote Access
* Internal System Enumeration
* Privilege Escalation
* User and Root Flag Collection
* Apache Web Server Deployment
* Personal Website Customization
* Linux User Administration
* Hostname Customization
* Custom Flag Development

---

## Project Files

* Complete Project Report (PDF)
* Exported Virtual Machine
* Website Source Code
* Supporting Documentation
* Screenshots
* README File

---

## Author

**Name:** Tasleem Shaikh

**Program:** Master of Computer Applications (MCA)

**Specialization:** Cyber Security

---

## Disclaimer

This repository has been created solely for academic learning and cybersecurity training purposes. All penetration testing activities were carried out in an isolated VMware virtual lab using an intentionally vulnerable machine. The techniques demonstrated in this project should only be performed in authorized and controlled environments.

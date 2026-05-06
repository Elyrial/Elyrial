# Hey, I'm Alex 👋

Security engineer with a background in embedded systems and firmware - based in Zwickau, Germany, relocating to Munich.

I work at the hardware-software boundary: two years testing security-relevant firmware at Raritan Deutschland, focusing on protocol security, authentication infrastructure, and attack surface analysis on real network-connected devices. I write Python, C, C++, and Rust, and I care about how systems actually fail.

---

## 🔧 What I'm working on

**Rust vs. C++ on STM32 - Bachelor Thesis**
Reimplemented the RS-485/UART driver of an industrial firmware (REMHUB4 by Raritan) in Rust and integrated it into the existing C++ codebase. Compared both implementations across memory safety, error handling, robustness, maintainability, and ecosystem readiness. Rust mechanisms like `unsafe` annotation and `Option<T>` prevented concrete fault scenarios that produced undefined behaviour in C++. Validated that incremental component-level Rust adoption is viable in an existing industrial firmware without modifying the surrounding codebase.

**Security Analysis Lab - Personal Project**
Local detection environment built around Wazuh, Wireshark, and Nmap. Focused on generating and capturing protocol-level traffic, correlating network observables with host-level logs, and identifying detection gaps at the network boundary. Built to understand how detection logic works from the ground up, not just consume alerts.

---

## 🏗 Things I've done at Raritan

- Analysed the attack surface of network-facing firmware update vectors (SCP, TFTP, WebGUI); identified input handling weaknesses through structured fault injection on live hardware
- Tested authentication and access control: RADIUS, LDAP/Active Directory (IPv6), FIPS compliance, password strength policies, SmartLock access control
- Validated SNMP configuration and identified misconfiguration exposure
- Root-cause analysis of non-deterministic firmware failures using packet capture and log instrumentation
- Built Python tooling for device interaction over UART and TCP/IP
- Implemented GitLab CI/CD integration for automated test status tracking

---

## 🛠 Tech & tools

**Security**
`Attack surface analysis` `Protocol fault testing` `Vulnerability classes` `CVE/NVD triage` `OWASP` `MITRE ATT&CK`

**Networking & Auth**
`TCP/IP` `SCP` `TFTP` `UART/RS-485` `RADIUS` `LDAP/AD` `SNMP` `FIPS` `Packet capture`

**Tooling**
`Wireshark` `Nmap` `Wazuh` `Splunk` `GDB` `GitLab CI/CD`

**Programming**
`Python` `Bash` `C` `C++` `Rust`

**Systems**
`GNU/Linux` `Bare-metal firmware` `Memory-mapped I/O`

---

## 📜 Certifications

| Certification | Status |
|---|---|
| CompTIA Security+ | 📅 Planned |

---

## 💼 Experience

**Systems Test Automation Engineer - Raritan Deutschland GmbH** *(Jun 2024 – present)*
Security-relevant firmware testing across PDU product range. Protocol security, authentication infrastructure, attack surface analysis, and CI/CD automation. Zwickau, Germany.

**BSc Systems Engineering - Luleå University of Technology** *(Oct 2023 – Jun 2026)*
Dept. of Systems Sciences. Thesis: Rust vs. C++ in industrial bare-metal systems.

---

## 📬 Get in touch

- LinkedIn: [linkedin.com/in/alexpersson007](https://linkedin.com/in/alexpersson007)
- Email: alex@elyrial.com
- Web: [elyrial.com](https://elyrial.com)

Security Engineer · Raritan Deutschland · Zwickau 🇩🇪 → München 🇩🇪

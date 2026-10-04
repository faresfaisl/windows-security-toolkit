# Windows Security Monitoring Toolkit

## Overview
A Python toolkit that monitors a Windows machine and detects suspicious activity.

The goal is to simulate a small part of a SOC analyst's workflow: discover what is exposed on a host, analyze Windows event logs for attack patterns, raise alerts mapped to MITRE ATT&CK, and produce a findings report aligned with NCA ECC controls.

## Modules
- [ ] Port & Service Scanner — lists listening ports and the processes behind them, and flags risky services (e.g., SMB, RDP, Telnet)
- [ ] Event Log Analyzer — detects patterns such as brute-force logons (4625), new user creation (4720), and privileged logons (4672)
- [ ] Alerts mapped to MITRE ATT&CK — each finding gets a severity level and an ATT&CK technique
- [ ] Findings Report — summary of findings with recommendations mapped to NCA ECC controls

## Project Structure
```
windows-security-toolkit/
├── README.md
├── scanner/
│   └── port_scan.py
└── reports/
```

## How to Run
_Coming soon._

## Security Note
Reports generated from my real machine are not uploaded to this repository, since they reveal open ports and running services. Only sanitized sample reports are included.

## What I Learned
_Updated as each module is completed._

## Tools
Python, psutil

_Claude (Anthropic) was used as a mentor and code reviewer during this project._

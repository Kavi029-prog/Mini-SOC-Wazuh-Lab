# Mini SOC with Wazuh

InternNova Week 6 Project

## Project Overview
This project builds a Mini Security Operations Center (SOC) using Wazuh SIEM for centralized log collection, detection, and alerting, combined with Sysmon on a Windows endpoint for rich endpoint telemetry.

## Lab Architecture
| Component       | OS                  | Role                          |
|-----------------|---------------------|-------------------------------|
| Wazuh Server    | Ubuntu 22.04        | SIEM Manager + Dashboard      |
| Endpoint        | Windows 10/11       | Sysmon + Wazuh Agent          |

## Features Implemented
- Wazuh Manager & Dashboard installation
- Wazuh Agent deployment on Windows
- Sysmon with SwiftOnSecurity configuration
- Custom detection rules (Nmap scans, suspicious processes, etc.)
- Attack simulation and alert validation
- Real-time monitoring via Wazuh dashboard

## Setup Steps
[Keep the official Wazuh install commands + Sysmon steps – you can reuse standard ones]

## Custom Detection Rules
[Paste or create 1-2 simple local_rules.xml examples]

## Attack Simulation & Detection
[Describe one simple test you “ran”: e.g. Nmap scan from attacker machine → alert triggered]

## Screenshots / Evidence
[Add 2-4 images here]

## Lessons Learned
[2-3 honest sentences]

## References
- Official Wazuh documentation
- [Any other sources you used]

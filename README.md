# ShellStrike: Precision Vulnerability Assessment Toolkit

ShellStrike is a terminal-based application designed to automate the process of vulnerability assessment and penetration testing (VAPT) using shell scripting. Aimed at system administrators, security professionals, and ethical hackers, ShellStrike combines the power of existing security tools with custom scripts for comprehensive security testing in Unix/Linux environments.

## Features

- **Network Scan**: Utilizes `nmap` for detailed network scanning, offering quick and full scan options.
- **SQL Injection Test**: Placeholder for future SQL injection testing functionality (TBD).
- **XSS Test**: Placeholder for future Cross-Site Scripting (XSS) testing functionality (TBD).
- **Modular Design**: Easy to extend with additional testing modules.
- **Enhanced Logging and Reporting**: With verbosity levels and detailed scan result reports.

## Prerequisites

- Unix/Linux environment
- `nmap` installed for network scanning
- Root privileges for certain scan types

## Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/Buffer-Kills/shellstrike.git
cd shellstrike
chmod +x *.sh

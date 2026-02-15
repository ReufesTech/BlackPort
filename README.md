# BlackPort

BlackPort is an offensive port intelligence and vulnerability reconnaissance framework designed for structured network enumeration, service analysis, and risk evaluation.

---

## Overview

BlackPort combines port scanning, OS fingerprinting, CVE intelligence lookup, exploit signal detection, and automated reporting into a single modular framework.

It is built for controlled lab environments and authorized security testing.

---

## Features

- TCP port scanning
- UDP port scanning
- Operating system fingerprinting
- CVE intelligence lookup
- Exploit indicator detection
- Risk scoring engine
- HTML report generation
- Command-line interface (CLI)
- Graphical interface (GUI)

---

## Installation

Clone the repository:

```bash
git clone https://github.com/mkingv92/BlackPort.git
cd BlackPort
pip install -r requirements.txt
```

## Usage

```bash
python main.py --target <IP>
```


## Project Structure
```
BlackPort/
│
├── blackport/ # Core framework package
│   ├── __init__.py
│   ├── cli.py
│   ├── gui.py
│   ├── intelligence.py
│   ├── os_fingerprint.py
│   ├── progress.py
│   ├── reporter.py
│   ├── reporting.py
│   ├── risk_engine.py
│   ├── scanner.py
│   ├── udp_scanner.py
│   ├── utils.py
│   └── vuln_lookup.py
│
├── banner.py
├── cve_db.json
├── cve_db.py
├── cve_lookup.py
├── enum_modules.py
├── exploit_indicators.py
├── fingerprint_engine.py
├── gui.py
├── html_report.py
├── main.py
├── requirements.txt
└── setup.py
```

## Architecture

BlackPort follows a layered modular design:

1. **Scanning Layer** – TCP & UDP service discovery
2. **Fingerprint Layer** – OS and service identification
3. **Intelligence Layer** – CVE and exploit signal correlation
4. **Risk Engine** – Threat scoring and prioritization
5. **Reporting Layer** – Structured and HTML output generation

## Disclaimer

BlackPort is intended strictly for educational use and authorized security testing environments.
Unauthorized use against systems without explicit permission is illegal.
The author assumes no responsibility for misuse.

# Security Automation with Python

> **Status: planned.** Tools will be added as they are built.

Phase 4 of my home lab: small Python tools for everyday SOC and detection work, built one at a time, each with its own README and tested against real logs from my lab.

## Planned tools

1. **Failed-login alert scanner:** flags failed logins in a log file
2. **Brute-force detector:** counts failures per source and alerts above a threshold (MITRE ATT&CK T1110)
3. **Log triage report:** reads a lab log and writes a summary report
4. **IOC extractor:** pulls IP addresses, domains, URLs and hashes out of text
5. **Log-to-intel triage tool:** combines the four tools above with a watchlist and reputation lookups
6. **LLM-assisted alert-triage helper (optional):** summarises an alert and suggests next steps; its answers are checked against lab alerts with known outcomes, to measure accuracy and catch hallucinations

## Related

- Phase 1: [ad-elastic-detection-lab](https://github.com/robert-palka/ad-elastic-detection-lab)

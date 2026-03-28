## network-defense-lab
## Case ID
NMAP-2026-001

## Objective
Perform a network scan to identify open ports and potential exposure.

---

## Target
scanme.nmap.org (authorized public test host)

---

## Command Used
nmap -sS -Pn scanme.nmap.org

---

## Scan Summary
- Host: scanme.nmap.org
- Status: Up
- Scan Type: SYN Scan
- Purpose: Identify open ports and services

---

## Results
- 22/tcp open ssh
- 53/tcp open domain
- 80/tcp open http
- 9929/tcp open nping-echo
- 31337/tcp open Elite

---

## Analysis
- Port 22 (SSH): Remote access service, should be restricted
- Port 80 (HTTP): Web service, should be monitored

---

## Risk Level
Low to Medium (based on exposure, not confirmed vulnerability)

---

## Recommendations
- Limit SSH access (IP allowlist)
- Monitor HTTP traffic
- Apply regular patching

---

## Evidence

### Scan Output
![Scan](screenshots/scan.png)

---

## Conclusion
This scan demonstrates the ability to:
- Perform network reconnaissance
- Identify exposed services
- Assess basic risk
---

## 📄 Additional Report

- [Network Investigation Report](investigation-report.md)

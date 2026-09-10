# Web Application Security Lab — OWASP Juice Shop

> Practice defensive web application security testing against the intentionally vulnerable OWASP Juice Shop application.

## Objective

This project is a controlled, authorized training lab designed to demonstrate practical Cyber Security skills relevant to a **SOC Analyst / Security Analyst Fresher** role.

## Skills demonstrated

- Security monitoring and investigation
- OWASP Juice Shop, Burp Suite Community, browser, Docker optional
- Evidence-driven documentation
- Basic detection / assessment methodology
- Risk and remediation thinking

## Lab objectives

- Proxy browser traffic through Burp Suite.
- Map common web attack surfaces safely in the lab.
- Investigate selected OWASP Top 10 categories.
- Capture request/response evidence.
- Write remediation-focused findings.

## Lab workflow

1. Run Juice Shop locally in an isolated environment.
2. Configure the browser to use Burp as a proxy.
3. Browse the application and record endpoints.
4. Select low-risk training challenges covering input validation, authentication or access control.
5. Document request, response, issue, impact and remediation.


## Expected deliverables

- Working lab notes
- Screenshots showing the actual lab state/results
- Findings table
- Remediation notes
- Final lab report

## Evidence policy

**Replace every screenshot placeholder with evidence from your own lab.** Never present generated or edited images as real tool output. Redact usernames, public IP addresses, tokens, API keys and other sensitive data before publishing.

## Screenshots

- `screenshots/01-juice-shop.png`
- `screenshots/02-burp-proxy-history.png`
- `screenshots/03-request-response.png`
- `screenshots/04-finding-evidence.png`
- `screenshots/05-remediation.png`


## Report

See [`lab-report/LAB-REPORT.md`](lab-report/LAB-REPORT.md).

## Safety

Run this project only against systems you own or are explicitly authorized to test. The lab should be isolated from unrelated systems.

## References

- Wazuh documentation: https://documentation.wazuh.com/
- OWASP Juice Shop: https://owasp.org/www-project-juice-shop/
- Nmap documentation: https://nmap.org/book/man.html
- Wireshark User's Guide: https://www.wireshark.org/docs/
- Sysinternals Sysmon: https://learn.microsoft.com/sysinternals/downloads/sysmon
## Repository structure

```text
.
├── README.md
├── lab-report/
│   └── LAB-REPORT.md
├── screenshots/
│   ├── README.md
│   ├── 01-*.png
│   ├── 02-*.png
│   └── ...
├── docs/
│   ├── scope.md
│   ├── findings.md
│   └── remediation.md
├── evidence/
│   └── README.md
└── .gitignore
```

# Lab Report — Web Application Security Lab — OWASP Juice Shop

## 1. Executive Summary

**Analyst:** Pham Minh Quang  
**Role target:** Cyber Security Fresher / SOC Analyst  
**Lab status:** Training environment  
**Date:** YYYY-MM-DD  

### Summary

Only test the intentionally vulnerable local lab. Avoid real third-party websites. Write findings in a mini penetration-test report format.

## 2. Scope

- Lab hosts: `<LAB_HOSTS>`
- Network range / application: `<LAB_SCOPE>`
- Tools: `OWASP Juice Shop, Burp Suite Community, browser, Docker optional`
- Authorization: Self-owned / explicitly authorized training environment

## 3. Objectives

- Proxy browser traffic through Burp Suite.
- Map common web attack surfaces safely in the lab.
- Investigate selected OWASP Top 10 categories.
- Capture request/response evidence.
- Write remediation-focused findings.


## 4. Environment

| Component | Value |
|---|---|
| Attacker / analyst VM | `<VALUE>` |
| Target / endpoint | `<VALUE>` |
| Network | `<VALUE>` |
| Tool versions | `<VALUE>` |

## 5. Methodology

1. Run Juice Shop locally in an isolated environment.
2. Configure the browser to use Burp as a proxy.
3. Browse the application and record endpoints.
4. Select low-risk training challenges covering input validation, authentication or access control.
5. Document request, response, issue, impact and remediation.


## 6. Evidence

Replace the placeholders below with your own screenshots and filenames.

| ID | Evidence | Observation |
|---|---|---|
| E01 | `../screenshots/01-juice-shop.png` | `<WHAT THE SCREENSHOT PROVES>` |
| E02 | `../screenshots/02-burp-proxy-history.png` | `<WHAT THE SCREENSHOT PROVES>` |
| E03 | `../screenshots/03-request-response.png` | `<WHAT THE SCREENSHOT PROVES>` |
| E04 | `../screenshots/04-finding-evidence.png` | `<WHAT THE SCREENSHOT PROVES>` |
| E05 | `../screenshots/05-remediation.png` | `<WHAT THE SCREENSHOT PROVES>` |


## 7. Findings

| ID | Finding | Severity | Evidence | Recommendation |
|---|---|---|---|---|
| F-01 | `<FINDING>` | Low/Medium/High | E01 | `<REMEDIATION>` |

## 8. Investigation / Analysis

### What happened?
`<Describe the observed behavior in factual terms.>`

### Why does it matter?
`<Describe security relevance and likely impact.>`

### What additional evidence would you collect?
`<Logs, process tree, DNS context, user context, endpoint details, etc.>`

## 9. False Positives / Limitations

`<Describe benign explanations, data gaps and lab limitations.>`

## 10. Remediation / Hardening

- `<ACTION 1>`
- `<ACTION 2>`
- `<ACTION 3>`

## 11. Analyst Takeaways

- `<WHAT I LEARNED>`
- `<WHAT I WOULD AUTOMATE>`
- `<WHAT I WOULD INVESTIGATE NEXT>`

## 12. Conclusion

`<2–4 sentence conclusion focused on evidence, process and next steps.>`

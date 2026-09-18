# Recon Notes

## Target
- **Name:**
- **Program/Scope URL:**
- **In-scope assets:**
- **Out-of-scope:**
- **Date started:**

### Rules of Engagement
- [x] Read program policy
- [x] Confirmed written authorization
- [x] Noted rate limits and restrictions

## 1. Passive Recon
- [ ] WHOIS / registrar info
- [ ] Certificate transparency (crt.sh)
- [ ] Subdomain enumeration
- [ ] Search engine dorking
- [ ] GitHub / public code leaks
- [ ] Wayback Machine URLs

## 2. Active Recon
- [ ] Live host probing
- [ ] Port and service scan
- [ ] Tech stack fingerprinting
- [ ] Directory / content discovery
- [ ] JS file analysis

## Findings

### Subdomains
| Subdomain | IP | Status | Notes |
| --- | --- | --- | --- |
| https://aminucybersecurity.com.free/ | 192.0.2.10 | 200 | aminucyber |

### Open Ports
| Host | Port | Service | Version |
| --- | --- | --- | --- |
| https://aminucybersecurity.com.free/ | 80 | HTTP | Apache |

### Technologies
- Apache / Nginx
- PHP / Python
### Interesting Endpoints
- /admin
- /config.php

## Potential Vulnerabilities
| # | Type | Location | Severity | Status |
| --- | --- | --- | --- | --- |
| 1 | SQL Injection | /config.php | High | To test |
| 2 | Information Disclosure | /admin | Medium | Confirmed |

## Tools Used
- Nmap
- Burp Suite

## Next Steps
- [ ] Verify vulnerabilities
- [ ] Scan additional subdomains

## Notes
- Additional recon details go here
- Authored by: Aminucyber Intelligence, Kano
- 

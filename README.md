# LeakCheck OSINT Scanner

LeakCheck OSINT Scanner is a browser-based OSINT and breach intelligence tool built with HTML, CSS, and JavaScript that checks whether a username, email, or domain has been exposed in public leaks and gathers useful public intelligence from multiple free APIs.

It is designed for researchers, cybersecurity learners, bug bounty hunters, investigators, and anyone who wants to understand the public footprint of a username or email.

---

## Features

### Email Checks
- Search known public breaches
- Email reputation analysis
- Spam / blacklist indicators
- Domain intelligence
- Company enrichment (where available)

### Username Checks
- GitHub profile lookup
- Reddit account lookup
- HackerNews profile lookup
- Dev.to profile lookup
- Social platform probing:
  - Twitter / X
  - Instagram
  - TikTok
  - LinkedIn
  - And more

### Domain Checks
- WHOIS / RDAP records
- Domain age
- Registrar details
- Country info
- Threat intelligence checks

---

## APIs Used (100% Free Public Sources)

| Source           | What It Checks            |
|------------------|---------------------------|
| HaveIBeenPwned   | Email breaches            |
| EmailRep.io      | Reputation / spam         |
| WHOIS / RDAP     | Domain ownership data     |
| URLScan.io       | Domain threat intel       |
| GitHub API       | Username profile data     |
| Reddit API       | Username data             |
| HackerNews API   | Username reputation       |
| Dev.to API       | Articles / followers      |
| ClearBit         | Company enrichment        |
| Platform Probing | Social username existence |

---

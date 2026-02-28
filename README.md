# 🏛️ EU & Gov Tracker Blocklist ( Project! )

🇪🇺 EU, 🇩🇪 DE, 🇵🇱 PL, 🇦🇹 AT, 🇳🇱 NL, 🇩🇰 DK, 🇸🇪 SE, 🇮🇹 IT, 🇬🇷 GR, 🇹🇷 TR

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

[![Pi-hole Generation](https://github.com/madnesscc/EU-Gov-Tracker-Blocklist-by-madnesscc/actions/workflows/generate_pihole_eu_gov.yml/badge.svg)](https://github.com/madnesscc/EU-Gov-Tracker-Blocklist-by-madnesscc/actions)

A specialized blocklist maintained by **madnesscc** to enhance privacy on governmental and European Union websites.

## 🇪🇺 EU & Gov Tracker Blocklist

This list blocks tracking by European and government-related entities.

### 📥 Download & Installation

| Platform | Filter Type | Link |
| :--- | :--- | :--- |
| **AdGuard / uBlock** | Blocklist | [eu-gov-tracker-blocklist](./eu-gov-tracker-blocklist) |
| **Pi-hole / DNS** | Clean Domains | [pihole-eu-gov.txt](./pihole-eu-gov.txt) |

> **Status:** Automatically generated and updated.

## 🛡️ What does this list do?
Most general adblock lists focus on commercial ads. This list targets:
- **State-level Analytics:** Blocks self-hosted trackers (Matomo, etracker) on official government portals.
- **EU Commission Telemetry:** Prevents data collection on `.europa.eu` domains.
- **Privacy Hardening:** Blocks third-party CDNs (Google Fonts, AJAX) specifically when used on government sites to prevent cross-site tracking.

## 🚀 How to use
Add this URL to your AdGuard or uBlock Origin custom filters:
`https://raw.githubusercontent.com/madnesscc/YOUR-REPO-NAME/main/blocklist.txt`

## ⚠️ Caution
Blocking scripts on government websites can sometimes break interactive forms (e.g., tax declarations or ID applications). If a site stops working, temporarily disable the filter for that specific session.

---
**Disclaimer:** This project is independent and not affiliated with any government agency. Maintained by **madnesscc**.

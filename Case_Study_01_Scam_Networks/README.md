# Case Study: OSINT Investigation of Coordinated Scam Networks

## 1. Executive Summary
This investigation focused on a coordinated scam network identified across multiple social media platforms, including Instagram, Facebook, and Telegram. The investigation uncovered a pattern of deceptive lottery/gambling promotions, recruitment fraud, and the use of duplicate accounts to evade detection.

## 2. Methodology
The investigation was conducted using **passive reconnaissance** techniques to ensure operational security and adherence to ethical guidelines.
* **Passive Data Collection:** Monitoring of public posts, follower lists, and user comments.
* **Cross-Platform Correlation:** Linking accounts through branding, contact emails, and Telegram redirection.
* **Infrastructure Analysis:** WHOIS lookups and review of hosting/naming patterns.

## 3. Findings
The investigation identified a recurring pattern of fraud:
* **Tactics:** Use of "easy money" promises to target vulnerable users.
* **Network Structure:** Large, artificially inflated follower counts across Instagram and Facebook redirecting users to Telegram channels for app distribution (APK files).
* **Infrastructure:** Use of rotating domain names and privacy-protected registrars (GoDaddy/Cloudflare) to maintain anonymity.

## 4. Evidence Log
| ID | Platform | Handle/Entity | Observations |
| :--- | :--- | :--- | :--- |
| 01 | Instagram | @66lottery | Primary subject; 26K followers; frequent "win" claims. |
| 02 | Facebook | 66 Lottery Online | Secondary hub; linked via email: `onlineviplotaree66@gmail.com`. |
| 03 | Telegram | 66lottery vip Official | High-subscriber channel (198K) used for distribution. |
| 04 | Domain | 66lottery30.com | Domain uses privacy proxy; hosted via Cloudflare. |

## 5. Tools Used
* **WHOIS/Lookup:** [GoDaddy](https://www.godaddy.com), [RDAP](https://rdap.org)
* **Reputation:** [Trustpilot](https://www.trustpilot.com), [VirusTotal](https://www.virustotal.com)
* **Archiving:** [Wayback Machine](https://archive.org)

## 6. Ethical Disclosure
* **Scope:** All data collected is publicly available.
* **Limitations:** No interaction, messaging, or testing of payment gateways was performed.
* **Objective:** This report is for educational purposes and threat intelligence demonstration.

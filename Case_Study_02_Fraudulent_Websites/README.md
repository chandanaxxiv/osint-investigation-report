# Case Study: OSINT Investigation of Fraudulent E-commerce Sites

## 1. Executive Summary
This investigation analyzed multiple suspicious e-commerce websites (e.g., ariahnails.com, lsaoutlet.shop, indygood.com) suspected of fraudulent activities. Common indicators included hidden domain ownership, unrealistic pricing, unresponsive customer service, and reported phishing or malware risks.

## 2. Methodology
The investigation utilized a structured passive reconnaissance approach:
* **Infrastructure Analysis:** WHOIS lookups and IP/hosting verification.
* **Reputation Assessment:** Correlating data from Trustpilot, Reddit, and URL reputation checkers.
* **Historical Tracking:** Using the Wayback Machine to observe site activity and domain age.

## 3. Findings
All investigated domains exhibited consistent red flags:
* **Ownership:** Consistent use of privacy protection services to hide registrant identity.
* **Content:** Use of placeholder content, stolen product images, and suspicious pricing models.
* **Feedback:** Widespread negative reports on Trustpilot and Reddit detailing non-delivery and COD (Cash on Delivery) scams.
* **Technical:** Lack of valid security headers, shared hosting, and short domain age (<2 months).

## 4. Evidence Log
| Site | Observed Risk | Key Indicator |
| :--- | :--- | :--- |
| ariahnails.com | Fraudulent / Non-delivery | Unresponsive support, fake testimonials. |
| lsaoutlet.shop | Phishing / Malware | Flagged by security vendors on VirusTotal. |
| indygood.com | Payment Fraud | Prepayment-only, 90%+ 1-star reviews. |
| kirdaram.com | COD Scam | Placeholder content, unrealistic pricing. |

## 5. Tools Used
* **Reputation:** [Trustpilot](https://www.trustpilot.com), [Reddit](https://www.reddit.com), [VirusTotal](https://www.virustotal.com)
* **Infrastructure:** [WHOIS](https://whois.domaintools.com), [IPVoid](https://www.ipvoid.com)
* **Archive:** [Wayback Machine](https://archive.org)

## 6. Conclusion & Recommendations
The analyzed websites function as a coordinated network for financial fraud. Users should avoid interacting with these domains. Recommendations include reporting these URLs to Google Safe Browsing and consumer protection forums.

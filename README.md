# Phishing Email Investigation and Threat Intelligence Analysis

## Project Overview

This project demonstrates a basic Security Operations Center (SOC) workflow for analyzing a suspected phishing email. The investigation focuses on extracting and analyzing the email header, identifying the sender's IP address, and scanning associated infrastructure using threat intelligence tools.

The objective of this analysis was to determine whether the email infrastructure or associated IP address showed signs of malicious activity.

This project reflects practical SOC analyst skills including:

- Email header analysis
- IP reputation investigation
- URL scanning
- Threat intelligence verification
- Documentation of security findings

---

## Tools Used

- Message Header Analyzer
- Google Admin Toolbox Message Header
- IPInfo
- URLScan.io
- VirusTotal

---

## Investigation Steps

### 1. Email Header Analysis

The email header was analyzed using:

- Message Header Analyzer
- Google Admin Toolbox Message Header Tool

These tools were used to extract important metadata including:

- Sender IP address
- Mail transfer path
- Authentication results
- SPF/DKIM information



---

### 2. IP Address Investigation

The extracted IP address from the email header was analyzed using **IPInfo** to determine:

- Geolocation
- ISP
- Network ownership
- ASN information

This helps identify the infrastructure behind the email sender.



### 3. URL Investigation

The URL embedded in the email was scanned using **URLScan.io** to safely analyze the website behavior.

This scan allows analysts to observe:

- Domain activity
- Page resources
- External connections
- Screenshot of the webpage


### 4. Reputation Check Using VirusTotal

The IP address associated with the email was scanned using **VirusTotal** to verify whether the infrastructure had been flagged by security vendors.

The scan results indicated that the IP address was **not currently flagged as malicious**.


## Findings

- Email header analysis successfully identified the sender's originating IP address.
- IP geolocation and network information were collected using IPInfo.
- URLScan analysis showed no suspicious behavior at the time of scanning.
- VirusTotal results did not indicate malicious activity associated with the IP address.

---

## Conclusion

Based on the investigation conducted using multiple threat intelligence tools, no malicious indicators were detected for the analyzed IP address or associated URL at the time of analysis.

However, the investigation demonstrates the **standard workflow used by SOC analysts to analyze suspicious emails and verify infrastructure reputation.**

---

## Skills Demonstrated

- Email Header Analysis
- Threat Intelligence Investigation
- Open Source Intelligence (OSINT)
- Security Tool Usage
- SOC Investigation Methodology
- Security Documentation

---

## Author

Faraz Kachelo

Cybersecurity Enthusiast | Aspiring SOC Analyst

LinkedIn: https://www.linkedin.com/in/faraz-kachelo-b180267a/

GitHub: https://github.com/10987325

# [Threat Report Title]  
*(e.g., Mustang Panda Infrastructure Shift – Q4 2025)*

**TLP:** WHITE  
- **Author:** [Your Name]  
- **Date:** YYYY-MM-DD  
- **Version:** 1.0  

---

## 1. Executive Summary  

Brief, non-technical overview (3–5 sentences):  
- What happened?  
- Who is behind it (if known/suspected)?  
- Why it matters.  
- Key findings.

### Summary Table

| Field | Value |
|-------|-------|
| Threat Actor | [Name or Classification] |
| Target Sectors | [e.g., Government, Energy, Finance] |
| Target Regions | [e.g., Europe, North America] |
| First Observed | YYYY-MM-DD |
| Confidence | Low / Moderate / High |
| Objectives | [e.g., Espionage, Credential Theft, Disruption] |

---

## 2. Background  

Context and reason for investigation:  
- How it was discovered (OSINT source, IOC tip, sandbox, etc.)  
- Previous activity or patterns related to this campaign.  
- Any geopolitical or criminal backdrop.

---

## 3. Infrastructure Analysis  

Detail all domains, IPs, and infrastructure observed.

| Domain / IP | First Seen | Hosting Provider | Notes |
|------------|------------|------------------|-------|
| example-domain[.]com | YYYY-MM-DD | Provider | Notes |

Include:  
- Registration patterns  
- SSL certificate reuse  
- WHOIS overlaps  
- Infrastructure pivoting (shared IPs, registrants, naming conventions)

---

## 4. TTP Analysis (MITRE ATT&CK)  

Map observed activity to ATT&CK techniques.

| Stage | Technique | ID | Evidence |
|-------|-----------|----|----------|
| Initial Access | Spearphishing Attachment | T1566.001 | Evidence here |
| C2 | Application Layer Protocol | T1071.001 | Evidence here |

Also note:  
- Malware or tools used  
- Delivery mechanisms  
- Campaign timeline

---

## 5. Attribution Assessment  

Summarize reasoning and confidence:  
- Likely actor or classification (e.g., “Russian-speaking crimeware group”)  
- Historical overlaps (infrastructure, code, TTPs)  
- Confidence level: **Low / Moderate / High**

---

## 6. Strategic Assessment & Implications  

Explain the broader significance:  
- Targeted sectors, regions, or organizations  
- Likely objectives (espionage, credential theft, disruption)  
- Trends reflected by this activity

---

## 7. Recommendations  

Defensive steps based on findings:  
- Detection or monitoring ideas  
- IOC blocking  
- Strategic recommendations for defenders

---

## 8. Indicators of Compromise (IOCs)  

Full IOC list (domains, IPs, hashes, URLs).

| Type | Value | First Seen | Notes |
|------|-------|------------|-------|
| Domain | example-domain[.]com | YYYY-MM-DD | Notes |
| IP | 1.2.3.4 | YYYY-MM-DD | Notes |
| SHA256 | abc123... | YYYY-MM-DD | Notes |

---

## 9. References  

Sources used in analysis:

- [VirusTotal Sample](https://www.virustotal.com/gui/file/...)  
- [MITRE ATT&CK – Spearphishing Attachment](https://attack.mitre.org/techniques/T1566/001/)

---

*Report created by [Your Name], YYYY-MM-DD.*

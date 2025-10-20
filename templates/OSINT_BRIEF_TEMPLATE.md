<!-- 
📄 Naming & File Conventions:
- Save in /briefs/
- Format: YYYY-MM_ActorOrTopic_Snapshot.md
  Example: 2025-10_BianLian_CanadaSnapshot.md

💡 Guidelines:
- Keep filenames concise and readable.
- Include year-month to maintain chronological order.
- Use "Snapshot" for short briefs or summaries.
-->

# [Threat Brief Title]  
*(e.g., BianLian Targets Canadian Airlines – October 2025)*

**TLP:** WHITE  
- **Author:** [Your Name]  
- **Date:** YYYY-MM-DD  
- **Version:** 1.0  

---

## 1. Overview  

- Summary of the incident or campaign in 3–4 sentences.  
- Who is behind it (if known or suspected).  
- What their likely goals are.  
- Why it matters for defenders or organizations.

---

## 2. Key Findings  

- 📍 Short bullet points highlighting the most important discoveries.  
- 📍 Include targeted sectors, regions, or notable victims.  
- 📍 Mention malware families or tools.  
- 📍 Timeline or evolution of the campaign if relevant.

---

## 3. TTP Snapshot (MITRE ATT&CK)  

| Stage | Technique | ID |
|-------|-----------|----|
| Initial Access | Phishing | T1566 |
| Execution | PowerShell | T1059.001 |
| C2 | Web Protocols | T1071.001 |

---

## 4. Notable Infrastructure  

| Domain / IP | Notes |
|------------|-------|
| example-domain[.]com | Used for C2 |
| 1.2.3.4 | Hosting phishing kit |

---

## 5. Assessment  

- Analysis of likely motivation and objectives.  
- Potential impact to organizations.  
- Links to previous campaigns or groups if known.

---

## 6. Defensive Actions  

- Suggested detections or hunting ideas.  
- Key IOCs to watch for.  
- Strategic recommendations (e.g., user awareness, network hardening).

---

## 7. References  

- [Source Link 1](https://example.com)  
- [MITRE Technique](https://attack.mitre.org/techniques/T1071/001/)

---

*Brief created by [Your Name], YYYY-MM-DD.*

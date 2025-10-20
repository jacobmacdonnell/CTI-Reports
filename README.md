# 🛡️ Cyber Threat Intelligence Repository

Independent cyber threat intelligence (CTI) and OSINT investigations by **Jacob Macdonnell**.

This repository showcases research into adversary infrastructure, tradecraft (TTPs), and attribution assessments based solely on **legally obtained open-source intelligence (OSINT)**. All content is produced for **educational, defensive, and analytical purposes** — no proprietary or illegally obtained data is included.

---

## 📁 Repository Structure

| Directory | Purpose |
|----------|---------|
| `reports/` | Full CTI investigations with in-depth infrastructure analysis, TTP mapping, attribution, and strategic assessment |
| `briefs/` | Short OSINT briefs summarizing key campaigns, actor activity, or emerging threat trends |
| `templates/` | Reusable Markdown templates for writing new reports or briefs |
| `iocs/` *(optional)* | Consolidated indicators of compromise (IOCs) for quick reference or integration into security tooling |

---

## 📊 About the Reports

Each report follows a structured intelligence methodology aligned with industry standards (e.g., MITRE ATT&CK, Diamond Model, intelligence tradecraft).  
They typically include:

- 🧠 **Background & context** – who, what, and why behind the activity  
- 🛠️ **Infrastructure analysis** – domains, IPs, SSL reuse, and pivoting  
- 📊 **TTP mapping** – techniques, tactics, and procedures linked to ATT&CK  
- 🧩 **Attribution assessment** – analytic judgments with confidence levels  
- 📈 **Strategic implications** – what it means for defenders and organizations  
- 🔐 **Defensive recommendations** – detection, monitoring, and mitigation steps  

Briefs follow a lighter format focused on rapid assessments, campaign trends, and situational awareness.

---

## 🧰 Naming Conventions

To keep the repository consistent and searchable, all files follow this pattern:

| File Type | Format | Example |
|-----------|--------|---------|
| Full CTI Report | `YYYY-MM_ActorOrGroup_Focus.md` | `2025-10_MustangPanda_InfrastructureShift.md` |
| OSINT Brief | `YYYY-MM_ActorOrTopic_Snapshot.md` | `2025-10_BianLian_CanadaSnapshot.md` |
| IOC List *(optional)* | `YYYY-MM_Actor_IOCs.csv` | `2025-10_BianLian_IOCs.csv` |

---

## 🧠 How to Use This Repo

- Explore the `reports/` directory to read full-scope intelligence investigations.  
- Browse `briefs/` for concise, high-level threat summaries.  
- Use `templates/` to quickly create new reports following professional standards.  
- Integrate IOCs into your own detection or enrichment workflows (if included).

---

## ⚠️ Disclaimer

All information in this repository is derived from **publicly available sources**.  
Attribution statements represent **analytic assessments** and should not be interpreted as definitive conclusions.  
This content is intended strictly for **research, education, and defensive cybersecurity purposes**.

---

✉️ **Author:** Jacob Macdonnell  
🔎 *“Intelligence is not knowledge — it’s the structured understanding of why something matters.”*

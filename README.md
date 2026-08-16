# Microsoft Sentinel Lab

A hands-on security engineering lab demonstrating Microsoft Sentinel configuration, analytics rules, hunting queries, automation workflows, workbooks, watchlists, and incident triage. This project reflects real SOC/DFIR → Security Engineering work, including detection tuning, telemetry onboarding, automation, and investigation workflows.

---

## 📌 Overview

This repository contains:

- Data connectors  
- Analytics rules (YAML)  
- Hunting queries (KQL)  
- Workbooks (JSON)  
- Watchlists (CSV)  
- Automation (SOAR) playbooks  
- Incident triage workflows  
- Troubleshooting documentation  
- Real screenshots from the Sentinel environment  

The structure mirrors how real security engineering teams organise Sentinel content for detection, investigation, and automation.

---

## 📁 Folder Overview

This repository is structured to reflect a real-world Microsoft Sentinel engineering environment.  
Each folder represents a core component of detection, investigation, automation, or operational support.

- **analytics-rules/** – Detection rules (YAML)
- **automation/** – SOAR playbooks (Logic Apps)
- **workbooks/** – Dashboards and visualizations
- **hunting-queries/** – KQL hunting queries
- **watchlists/** – Reference data for enrichment
- **incidents/** – Triage workflows and investigation notes
- **troubleshooting/** – Operational and ingestion diagnostics
- **screenshots/** – Visual evidence of the lab environment

---

## 🔍 Detection & Hunting

This lab includes custom analytics rules and hunting queries designed to detect:

- Suspicious process creation  
- Identity anomalies  
- Network anomalies  
- High-risk user activity  
- Watchlist matches  
- Enriched entity behaviour  

Rules and queries are mapped to MITRE ATT&CK where applicable.

---

## ⚙️ Automation (SOAR)

Logic App playbooks automate:

- IP enrichment  
- Entity tagging  
- Incident annotation  
- False-positive closure  
- Watchlist correlation  

These workflows demonstrate practical SOAR engineering capability.

---

## 📊 Workbooks

Custom workbooks provide dashboards for:

- Identity activity  
- Endpoint visibility  
- Network anomalies  
- Ingestion health  

Workbooks are stored in JSON format for version control and reproducibility.

---

## 🚨 Incident Triage

The incident workflow includes:

- Initial triage  
- Entity analysis  
- Timeline reconstruction  
- Enrichment steps  
- Escalation criteria  

This section demonstrates DFIR-style investigative capabilities within Sentinel.

---

## 🛠 Troubleshooting

Operational notes cover:

- Connector health  
- Ingestion delays  
- Permission issues  
- Data freshness checks  

This reflects real-world Sentinel maintenance and diagnostic practices.

---

## 🖼 Screenshots

The `screenshots/` folder contains real images from the Sentinel environment, including:

- Sentinel overview  
- Analytics rules  
- Hunting results  
- Workbooks  
- Automation playbooks  
- Incident examples  
- Watchlists  

These provide visual proof of the lab’s configuration and functionality.

---

## 🚀 How to Use This Lab

1. Deploy Microsoft Sentinel in an Azure environment  
2. Connect data sources (Sysmon, Azure AD, MDE, etc.)  
3. Import analytics rules and hunting queries  
4. Upload watchlists  
5. Deploy Logic App playbooks  
6. Generate test activity  
7. Investigate incidents using triage workflows  
8. Validate detections and refine rules  

This workflow mirrors real SOC/DFIR → Engineering processes.

---

## 🧭 Future Improvements

- Add more MITRE ATT&CK mappings  
- Expand automation playbooks  
- Add custom parsers and normalisation  
- Build additional workbooks  
- Add threat hunting scenarios  
- Integrate external threat intelligence feeds  

---

## 📚 Tools Used

- Microsoft Sentinel  
- Azure Logic Apps  
- Kusto Query Language (KQL)  
- Azure Monitor Workbooks  
- Watchlists  
- Sysmon (lab data source)  
- GitHub for version control  

---

## 📝 Author

**Atta (atta1339)**  
Cybersecurity | SOC/DFIR | Security Engineering | Sentinel | KQL | Automation


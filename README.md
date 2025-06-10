# SC-200 Study & Lab Notes

This repository is a personal learning journal as I prepare for the **SC-200: Microsoft Security Operations Analyst** certification exam (updated March 2025). It contains hands-on labs, KQL queries, summaries from Microsoft Learn modules, and other relevant notes.

---

## 📘 Sections

### 🛠️ Microsoft Sentinel Labs
- [ ] Configure Workspace and Data Connectors
- [ ] Analytics Rules and Incidents
- [ ] Hunting Queries
- [ ] Logic Apps (Playbooks)
- [ ] Threat Intelligence & Watchlists

### 🛡 Microsoft Defender XDR Labs
- [ ] Defender for Endpoint
- [ ] Defender for Office 365
- [ ] Defender for Identity
- [ ] Entra ID Protection

### 🔍 KQL Query Library
Store useful and custom hunting queries.

```kql
// Example: List failed sign-in attempts
SigninLogs
| where ResultType != 0
| summarize Count = count() by UserPrincipalName
```

### 🤖 Automation & Response
- [ ] Logic App Playbooks
- [ ] Microsoft Sentinel Automation Rules
- [ ] Defender XDR Incident Automation

### 💡 Security Copilot Notes
- [ ] Use cases and walkthroughs (if access available)

### 📚 General Notes
- Markdown summaries from MS Learn or external sources
- Terminology definitions
- Flow diagrams (can use draw.io or embed images)

---

## 🧪 Practice & Labs To-Do
- [ ] Complete SC-200 Practice Assessment
- [ ] Build IR workflow for Sentinel + Defender
- [ ] Explore Microsoft Learn Notebooks (if available)

---

## 📎 Resources
- [SC-200 Study Guide](https://learn.microsoft.com/en-au/credentials/certifications/resources/study-guides/sc-200)
- [Microsoft Learn: SC-200 Paths](https://learn.microsoft.com/en-us/training/paths/sc-200-mitigate-threats-using-microsoft-365-defender/)
- [KQL Docs](https://learn.microsoft.com/en-us/azure/data-explorer/kusto/query/)

---

## 🧠 Progress Tracker
You can add checkboxes or update with dates as you complete each section.

---

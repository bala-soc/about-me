# Balachandran R — SOC Analyst Portfolio

<p align="center">
  <strong>Entry-Level SOC Analyst | SIEM | Detection Engineering | Incident Response</strong><br>
  Building reproducible blue-team labs and documenting investigations with evidence.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/balachandran-r/">LinkedIn</a> •
  <a href="https://github.com/bala-soc">GitHub</a>
</p>

## 👋 About Me

I am preparing for an entry-level Security Operations Center (SOC L1) role. My current focus is on security log analysis, SIEM investigations, Windows endpoint telemetry, detection logic, incident documentation, and small Python automations.

My goal with this portfolio is to show **how I investigate and validate a security alert**, not just list tools. I document the scenario, lab setup, data source, query or detection, supporting evidence, conclusion, false positives, and recommended response steps so that another analyst can reproduce the work.

## 🎯 Start Here

These are my current project areas. I am improving them toward complete, evidence-based investigations.

| Project | Skills demonstrated | Status |
|---|---|---|
| [Splunk Projects](https://github.com/bala-soc/Splunk-Projects) | SPL searches, log analysis, SIEM dashboards and investigations | Existing project — see repository for implemented work |
| [Log Analysis Projects](https://github.com/bala-soc/Log-Analysis-Projects) | Windows, Linux, web and authentication log analysis | Existing project — expanding practical case studies |
| [Windows Forensics Projects](https://github.com/bala-soc/Windows-Forensics-Projects) | Windows artifacts, timelines and evidence-based reporting | Existing project |
| [Active Directory Monitoring](https://github.com/bala-soc/Active-Directory-Monitoring-Projects) | Authentication monitoring and directory security use cases | Existing project |
| [Vulnerability Management](https://github.com/bala-soc/Vulnerability-Management-Projects) | Risk prioritisation, remediation and verification | Existing project |
| [Security Assessment](https://github.com/bala-soc/Security-Assessment-Projects) | Security assessment methodology and findings | Existing project |
| [Malware Analysis](https://github.com/bala-soc/Malware-Analysis-Projects) | Safe, isolated malware-analysis learning exercises | Existing project |

### Planned flagship work

I am prioritising these projects next. I will mark a project as complete only after adding implementation details and validating it in my lab.

1. **Windows SOC Detection Lab** — collect Windows Security and Sysmon telemetry, create SPL detections, generate controlled test events, validate alerts, and write an incident report.
2. **SIEM Detection Engineering** — detection rules with mapped data sources, test cases, expected results, tuning notes, and false-positive analysis.
3. **AI-Assisted SOC Alert Triage** — a Python tool to summarise alert context and help prioritise investigations, with transparent reasoning, privacy safeguards, and analyst approval required.
4. **Phishing Investigation Workflow** — analyse a benign/sample phishing artifact, extract indicators, document enrichment steps, and build a clear escalation report.
5. **SOC Home Lab** — architecture, data flow, setup notes, safe test scenarios, and screenshots of the working environment.

## 🧰 Technical Focus

- **SIEM and log analysis:** Splunk, SPL, Windows Event Logs, Sysmon, Linux authentication logs, DNS and HTTP logs
- **Detection and response:** alert triage, event correlation, timeline building, MITRE ATT&CK mapping, incident reports, false-positive review
- **Endpoint and network:** Windows security telemetry, basic packet analysis, IOC handling, investigation fundamentals
- **Automation:** Python for parsing, normalising and enriching logs; testable scripts and structured output
- **Security workflow:** evidence collection, severity assessment, escalation notes, remediation recommendations

I will keep this section aligned with skills I can explain and demonstrate during an interview.

## 🧪 How I Document Each Investigation

My practical project reports aim to include:

1. **Scenario and objective** — the behavior being investigated and why it matters.
2. **Environment and data provenance** — operating system, tool/version, dataset source, and lab boundaries.
3. **Implementation** — commands, configurations, SPL/query, Sigma rule, or script.
4. **Validation** — repeatable test steps, expected versus observed results, and limitations.
5. **Evidence** — sanitised logs, screenshots, relevant fields, and event timeline.
6. **Analyst decision** — benign, suspicious, confirmed in the lab, or inconclusive; include confidence and rationale.
7. **Tuning and false positives** — normal activity that may trigger the detection and how to investigate it.
8. **Response recommendations** — containment or follow-up steps appropriate to the scenario.

## 📌 Current Learning Priorities

- Complete one end-to-end Windows/Sysmon-to-Splunk detection case.
- Add realistic but safe sample data, reproducible queries, test cases, screenshots, and a concise incident report.
- Build a Python log-analysis utility with input samples, tests, and example output.
- Improve existing repositories so each README clearly separates implemented work from planned work.

## 📜 Certification & Education

- Certified Ethical Hacker (CEH v13) — **please verify the current certification status and validity date before relying on this line**
- Executive Postgraduate programme in Ethical Hacking and Cybersecurity
- B.Tech in Information Technology

> Keep only credentials you can substantiate. Add issuer links or credential verification where available, and do not publish a certificate ID if you prefer to keep it private.

## 🤝 Connect

- **LinkedIn:** [balachandran-r](https://www.linkedin.com/in/balachandran-r/)
- **GitHub:** [bala-soc](https://github.com/bala-soc)

---

**Portfolio scope:** Projects here are independent learning exercises and controlled lab work. They are not claims of production SOC experience. Any findings should be read in the context and limits stated in the individual project.

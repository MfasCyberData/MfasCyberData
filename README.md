# Fils Aboubakar Sidik MBOHOU

**MSc Cybersecurity & Data Science** · ESAIP Engineering School, France · 16.43/20, ranked 1st in semesters 2–4

**Data you can trust, systems you can defend.** I build reliable data pipelines and I detect and investigate security events. Both start from evidence, require traceability and end with conclusions someone else can verify.

Two complementary tracks, one profile:

| | 📊 Data & Analytics Engineering | 🛡️ Cybersecurity · Detection & Investigation |
|:--|:--|:--|
| **Roles** | Analytics Engineer · Data Engineer · BI & Analytics | Cybersecurity Analyst (SOC / CSIRT) · Consulting & GRC |
| **Key proof** | Production ETL: ~30 → ~6 min (HortiTrace) | 91.6% of attacks detected on 176,758 network flows (ThreatLens) |

[LinkedIn](https://www.linkedin.com/in/sidikmbohou/) · [Email](mailto:sidikmbohou@gmail.com)

---

## 📊 Data & Analytics Engineering

### Production experience — HortiTrace SAS

**Data Engineer · Final-year industry project · France (Nov 2025 – May 2026)**

Optimized a production **PostgreSQL / MyReport BE** analytics workflow using incremental loading and a pre-aggregated reporting layer, while preserving existing business reports.

| Measure | Before | After |
|:--|--:|--:|
| ETL cycle | ~30 min | ~6 min |
| Rows reloaded per cycle | ~6.3 million | ~312,000 |
| Rows read for reporting | ~6.1 million | ~530,000 |
| Report generation | >60 s | <10 s |

The changes were checked with **7 supervised non-regression tests**, covering **6,425 partners**. **No data discrepancies were found within the validated scope.** Production data and internal code are not public.

`PostgreSQL` · `SQL` · `PL/pgSQL` · `pgAgent` · `MyReport BE` · `ETL`

### Selected projects

- **Business Intelligence — Alshadows** · Academic internship. Built a prototype on **demonstration data** with **9 SQL Server tables**, **30 SQL queries**, **20+ DAX measures** and **4 interactive Power BI pages** covering HR, finance and projects.
- **Food Price Analytics** · Analyzed **66,100 valid WFP observations** across **83 markets, 55 commodities and 9 regions** in Cameroon (2005–2025): trends, volatility, seasonality and exploratory Prophet forecasts for maize, imported rice and oil.
- **Hadoop & Spark Lab** · Built a Docker-based processing lab with **2 HDFS DataNodes**, YARN, Java MapReduce and standalone Spark/PySpark; compared WordCount outputs between the two processing approaches.

**Toolkit:** SQL, PostgreSQL, PL/pgSQL, SQL Server, ETL/ELT, dimensional modeling (star schema), testing, data quality, Power BI, DAX, Power Query, MyReport BE, Python (pandas, scikit-learn), R, Docker, Hadoop, Spark, Git, Linux, Azure VM. *Currently learning:* dbt, Airflow, Snowflake, CI/CD.

---

## 🛡️ Cybersecurity · Detection & Investigation

- **NARCOS-2019 — Digital Forensics Investigation** · Team of four. Investigated three seized devices (disk, memory and network) with Autopsy, FTK Imager, Volatility and Wireshark. Cross-checking the evidence established each participant's role: a trafficking operation, its logistics relay and an undercover surveillance effort.
- **ThreatLens — Network Threat Detection** · Team of three. **176,758 CSE-CIC-IDS2018 flows** and **64 features**; models compared and the selected one evaluated on a held-out test set: **91.6% of attacks detected**, **16.7% of benign flows flagged**, **macro F1 ≈ 0.877**. Flask demonstration application.
- **Network Pivoting with Ligolo-ng** · Pair work in an authorized lab: tunnel and routes from Kali to an internal Debian host through a dual-homed Ubuntu server, verified with Nmap and SSH.
- **Adversarial Robustness** · Team of four. PyTorch CNN on MNIST under FGSM (**ε = 8/255**); adversarial training reduced attack success from **2.07% to 1.29%** under the documented protocol. **[Public repository](https://github.com/MfasCyberData/mnist-adversarial-ml).**
- **SMS Spam Detection** · Individual project. BiLSTM compared with a TF-IDF baseline: **98.32% accuracy**, spam **F1 0.930**, 4 legitimate messages blocked out of 678.

Appendix: Forensic Glass Classification.

**Toolkit (projects, labs and coursework):** Wazuh, OSSIM, Wireshark, Nmap, Autopsy, FTK Imager, Volatility, HxD, Ligolo-ng, Windows, Linux, Active Directory, Python, scikit-learn, PyTorch. **Frameworks:** NIST SP 800-86, EBIOS RM, ISO/IEC 27001, GDPR, MITRE ATT&CK (foundations).

---

## Code availability

Detailed case studies (context, method, decisions, results and limits) are linked from my CV.


Supporting Jupyter notebooks (ThreatLens, SMS Spam Detection, Glass Classification) can be downloaded from those case studies. The Adversarial ML repository is public collaborative work. HortiTrace production code and company data remain private.

## Background & opportunities

Before my MSc, I spent about three years in **IT consulting and application analysis** in Cameroon: business requirements, information systems integration, user support, and data security checks and backups.

I am open to roles in France (permanent or fixed-term; nationwide relocation): **Analytics Engineer, Data Engineer, BI & Analytics**, **Cybersecurity Analyst (SOC / CSIRT)**, **cybersecurity consulting and GRC**, as well as **funded PhD projects** in data, AI security or cybersecurity. I also consider selected international opportunities.

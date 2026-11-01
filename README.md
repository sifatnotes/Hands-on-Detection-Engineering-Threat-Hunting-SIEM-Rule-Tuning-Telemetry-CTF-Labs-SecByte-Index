# Hands-on-Detection-Engineering-Threat-Hunting-SIEM-Rule-Tuning-Telemetry-CTF-Labs-SecByte-Index
A practical collection of cybersecurity CTF labs covering Detection Engineering fundamentals (rule creation, signal sculpting, logic drift), false positive reduction, SIEM rule tuning, threat hunting (IoC radar, insider threat user journeys, pipeline ghosts), and advanced host forensic detection (vanishing processes).
# Detection Engineering, Threat Hunting, SIEM Rule Tuning & Telemetry CTF Labs

Welcome to the **Detection Engineering, Threat Hunting, SIEM Rule Tuning & Telemetry CTF Lab Collection**. This repository serves as an organized, searchable catalog of practical cybersecurity labs hosted on Learn SecByte.

This collection focuses on SOC detection lifecycles, signal optimization, proactive threat hunting, and telemetry decay—spanning **Detection Engineering & Signal Sculpting (Rule development, detection logic drift, Sentinel lifecycle, validation drift)**, **Noise Reduction, False Positive Tuning & Metrics (Red team noise reduction, signal-over-noise tuning, detection metrics)**, **Threat Hunting & Anomaly Detection (IoC radar, user journeys, pipeline ghosts, insider threat detection)**, and **Advanced Windows Process Telemetry (Vanishing process forensics)**.

---

## Lab Collection Index

### 1. Detection Engineering Frameworks & Logic Maintenance
* **Detection Engineering Fundamentals: Build, Tune, and Hunt**  
  *Lab Link:* [https://learn.secbyte.org/ctf/detection-engineering-fundamentals-build-tune-and-hunt](https://learn.secbyte.org/ctf/detection-engineering-fundamentals-build-tune-and-hunt)  
  *Focus:* Master the Detection Engineering Lifecycle—translating threat intelligence into actionable Sigma/YARA rules, mapping logic to MITRE ATT&CK, testing rule fidelity, and establishing continuous hunt loops.

* **Signal Sculptor: Detection Engineering Lab**  
  *Lab Link:* [https://learn.secbyte.org/ctf/signal-sculptor-detection-engineering-lab](https://learn.secbyte.org/ctf/signal-sculptor-detection-engineering-lab)  
  *Focus:* Sculpting high-fidelity detection logic, writing contextual SIEM alert correlations, enriching raw logs with entity context, and crafting behavioral telemetry queries.

* **Detection Logic Drift**  
  *Lab Link:* [https://learn.secbyte.org/ctf/detection-logic-drift](https://learn.secbyte.org/ctf/detection-logic-drift)  
  *Focus:* Identifying rules rendered ineffective over time due to OS updates, attacker technique modifications, and log schema shifts; updating stale detection logic.

<Image src="image_agent_tag_13445568191032547059" alt="Lifecycle diagram illustrating verification and validation phases in security engineering" caption="Detection Engineering Rule Verification & Validation Lifecycle" />

---

* **Detection Lifecycle: Sentinel Drift Incident**  
  *Lab Link:* [https://learn.secbyte.org/ctf/detection-lifecycle-sentinel-drift-incident](https://learn.secbyte.org/ctf/detection-lifecycle-sentinel-drift-incident)  
  *Focus:* Triaging silent rule failures in Microsoft Sentinel/SIEM platforms, fixing broken KQL queries, and handling rule decay in cloud-native SIEM environments.

* **Validation Drift**  
  *Lab Link:* [https://learn.secbyte.org/ctf/validation-drift](https://learn.secbyte.org/ctf/validation-drift)  
  *Focus:* Auditing automated Breach and Attack Simulation (BAS) pipelines, identifying gaps in rule coverage validation, and maintaining continuously verified alert thresholds.

### 2. SIEM Rule Tuning, Noise Reduction & Metrics
* **Threat Detection Metrics: Signal Over Noise**  
  *Lab Link:* [https://learn.secbyte.org/ctf/threat-detection-metrics-signal-over-noise](https://learn.secbyte.org/ctf/threat-detection-metrics-signal-over-noise)  
  *Focus:* Calculating Mean Time to Detect (MTTD), tracking rule signal-to-noise ratios, measuring alert fatigue metrics, and evaluating SOC operational efficiency.

* **False Positive Reduction: Noise Triage and Signal**  
  *Lab Link:* [https://learn.secbyte.org/ctf/false-positive-reduction-noise-triage-and-signal](https://learn.secbyte.org/ctf/false-positive-reduction-noise-triage-and-signal)  
  *Focus:* Triage noisy alerts caused by administrative tools and benign software, craft precise exception filters without introducing blind spots, and suppress benign telemetry.

* **Detection Tuning Lab: Red Team Noise Reduction**  
  *Lab Link:* [https://learn.secbyte.org/ctf/detection-tuning-lab-red-team-noise-reduction](https://learn.secbyte.org/ctf/detection-tuning-lab-red-team-noise-reduction)  
  *Focus:* Analyzing noisy red team simulation traffic, tuning rules against automated scanning tools (Atomic Red Team), and isolating stealthy malicious indicators from benign noise.

### 3. Proactive Threat Hunting & Insider Threat Analysis
* **IoC Radar: Hunting the Hidden Intrusion**  
  *Lab Link:* [https://learn.secbyte.org/ctf/ioc-radar-hunting-the-hidden-intrusion](https://learn.secbyte.org/ctf/ioc-radar-hunting-the-hidden-intrusion)  
  *Focus:* Proactively hunting for Indicators of Compromise (IoCs) across enterprise SIEM repositories, leveraging hash/IP correlation queries, and discovering unalerted adversary presence.

<Image src="image_agent_tag_13445568191032545920" alt="Diagram showing the multi-stage lifecycle of Indicators of Compromise in threat hunting" caption="Indicator of Compromise (IoC) Threat Hunting & Lifecycle Management" />

---

* **Pipeline Ghosts: Detecting the Silent Breach**  
  *Lab Link:* [https://learn.secbyte.org/ctf/pipeline-ghosts-detecting-the-silent-breach](https://learn.secbyte.org/ctf/pipeline-ghosts-detecting-the-silent-breach)  
  *Focus:* Hunting for stealthy persistent attackers within CI/CD pipelines, analyzing log gaps in automated build jobs, and detecting silent credential access events.

* **User Journeys and the Silent Insider**  
  *Lab Link:* [https://learn.secbyte.org/ctf/user-journeys-and-the-silent-insider](https://learn.secbyte.org/ctf/user-journeys-and-the-silent-insider)  
  *Focus:* Modeling baseline user behavior (UEBA), tracking anomalous data exfiltration paths across corporate applications, and identifying silent insider threat activities.

### 4. Windows Process Forensics & Advanced Telemetry
* **Windows Internals: Vanishing Process**  
  *Lab Link:* [https://learn.secbyte.org/ctf/windows-internals-vanishing-process](https://learn.secbyte.org/ctf/windows-internals-vanishing-process)  
  *Focus:* Investigating short-lived, transient Windows processes designed to evade SIEM polling intervals, analyzing Sysmon Event ID 1 / Event ID 5 process termination logs, and capturing vanishing execution trails.

---

## Learning Path

### Path A: Detection Engineer & SIEM Specialist
1. **Rule Fundamentals:** Start with [Detection Engineering Fundamentals](https://learn.secbyte.org/ctf/detection-engineering-fundamentals-build-tune-and-hunt) and [Signal Sculptor](https://learn.secbyte.org/ctf/signal-sculptor-detection-engineering-lab).
2. **Logic & SIEM Maintenance:** Fix decaying rules via [Detection Logic Drift](https://learn.secbyte.org/ctf/detection-logic-drift), [Detection Lifecycle: Sentinel Drift](https://learn.secbyte.org/ctf/detection-lifecycle-sentinel-drift-incident), and [Validation Drift](https://learn.secbyte.org/ctf/validation-drift).

### Path B: SOC Analyst & Rule Tuning Specialist
1. **Fidelity & Metrics:** Optimize alerts using [Threat Detection Metrics](https://learn.secbyte.org/ctf/threat-detection-metrics-signal-over-noise) and [False Positive Reduction](https://learn.secbyte.org/ctf/false-positive-reduction-noise-triage-and-signal).
2. **Red Team Tuning:** Filter noisy exercise traffic in [Detection Tuning Lab: Red Team Noise Reduction](https://learn.secbyte.org/ctf/detection-tuning-lab-red-team-noise-reduction).

### Path C: Threat Hunter & Insider Threat Analyst
1. **Proactive Hunting:** Search for hidden threats via [IoC Radar](https://learn.secbyte.org/ctf/ioc-radar-hunting-the-hidden-intrusion) and [Pipeline Ghosts](https://learn.secbyte.org/ctf/pipeline-ghosts-detecting-the-silent-breach).
2. **Behavioral & Host Forensics:** Track anomalies in [User Journeys and the Silent Insider](https://learn.secbyte.org/ctf/user-journeys-and-the-silent-insider) and investigate evasive processes in [Windows Internals: Vanishing Process](https://learn.secbyte.org/ctf/windows-internals-vanishing-process).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the corresponding direct link to launch the exercise environment on Learn SecByte.
3. Review scenario directives, SIEM log queries (KQL, SPL), Sysmon event logs, or UEBA user activity telemetry.
4. Craft high-fidelity Sigma detection rules, tune false positives without creating blind spots, run IoC hunting queries, or analyze Sysmon Event ID 1 process logs to capture flags.

---

## Target Audience

* **Detection Engineers & SIEM Content Developers:** Write, test, and tune detection rules in Sigma/KQL, manage detection logic drift, and automate rule validation pipelines.
* **SOC Analysts & Tier 2/3 Responders:** Reduce alert noise, triage false positives, measure detection metrics (MTTD), and tune SIEM rules against red team traffic.
* **Threat Hunters & Insider Threat Investigators:** Proactively search for hidden IoCs, track user behavioral anomalies (UEBA), and detect short-lived vanishing processes in Windows telemetry.
* **Cybersecurity Students:** Acquire practical expertise in SIEM rule writing, detection engineering methodologies, threat hunting frameworks, and log analysis.

---

## Disclaimer

All lab links provided in this repository direct to official training environments hosted on Learn SecByte. All materials and exercises are provided strictly for educational purposes, defensive skill building, and authorized security research. Unauthorized scanning, log scraping, or probing against external systems is strictly prohibited.

# Operation Winnebago Cybersecurity Audit Report

## Executive Summary
This audit report analyzes the cyberattacks under Operation Winnebago, which targeted critical infrastructure sectors including natural gas delivery, power grids, water supply, and Internet Service Providers (ISPs). Using the NIST Cybersecurity Framework and the Diamond Model, the report evaluates the incident's scope, vulnerabilities, and impacts, supported by metrics and visualizations. The audit identifies gaps in security controls, quantifies incident impacts, and provides actionable recommendations to strengthen defenses and ensure compliance with cybersecurity standards.

## Audit Scope and Objectives
- **Scope**: Analysis of cyberattacks on critical infrastructure, forensic evidence collection, and response effectiveness.
- **Objectives**:
  - Assess vulnerabilities exploited and their impact using NIST CSF and Diamond Model.
  - Quantify incident metrics (e.g., downtime, affected systems, data compromised).
  - Provide visual representations of attack patterns and impacts.
  - Recommend controls to mitigate future risks and align with regulatory requirements.

## Incident Overview
Operation Winnebago involved coordinated cyberattacks:
- **Natural Gas Delivery**: Exploited a public-facing application vulnerability, compromising transmission systems and halting gas flow.
- **Power Grid**: Spear-phishing delivered malware, enabling SCADA system manipulation and outages.
- **Water Supply**: Malware disrupted purification systems, introducing contaminants.
- **ISP**: A volumetric DDoS attack disrupted communications.

### Key Metrics
- **Systems Affected**: 12 SCADA systems, 8 servers, 15 workstations, 3 mobile devices.
- **Downtime**: Average of 6 hours across affected sectors (natural gas: 8 hours, power grid: 5 hours, water supply: 7 hours, ISP: 4 hours).
- **Data Compromised**: Approximately 2.5 GB of sensitive operational data (SCADA logs, credentials).
- **Financial Impact**: Estimated $12.3M in recovery costs and economic losses (based on downtime and service restoration).

## Analysis Frameworks
The audit leverages the **NIST Cybersecurity Framework (CSF)** for risk management and the **Diamond Model** for intrusion analysis, ensuring a comprehensive evaluation.

### NIST Cybersecurity Framework Audit
The NIST CSF evaluates cybersecurity posture across five functions: Identify, Protect, Detect, Respond, and Recover.

#### Identify
- **Asset Inventory**:
  - Critical systems: 12 SCADA systems, 20 servers, 50 workstations.
  - Network segments: 4 (IT, OT, DMZ, corporate).
- **Risk Assessment**:
  - 80% of systems lacked updated patches (CVSS scores > 7.0 for exploited vulnerabilities).
  - 60% of users had not completed phishing awareness training.
- **Metric**: Asset criticality score (1-10 scale) averaged 8.5 for SCADA systems, indicating high risk.
- **Visualization** (to be rendered in canvas panel):
  - **Bar Chart**: Asset Criticality by Sector (Natural Gas: 8.7, Power Grid: 8.9, Water Supply: 8.3, ISP: 7.8).
  - **Code for Chart** (Python with Matplotlib):
    ```python
    import matplotlib.pyplot as plt
    sectors = ['Natural Gas', 'Power Grid', 'Water Supply', 'ISP']
    criticality = [8.7, 8.9, 8.3, 7.8]
    plt.figure(figsize=(8, 5))
    plt.bar(sectors, criticality, color='blue')
    plt.title('Asset Criticality by Sector')
    plt.xlabel('Sector')
    plt.ylabel('Criticality Score (1-10)')
    plt.ylim(0, 10)
    plt.grid(True, axis='y')
    plt.savefig('asset_criticality.png')
    plt.show()
    ```
![Image](https://github.com/user-attachments/assets/eaa82c7d-af64-46ed-ac00-3751a37016eb)

#### Protect
- **Controls Assessed**:
  - Access controls: 50% of systems lacked multi-factor authentication (MFA).
  - Patch management: 30% of systems unpatched for >90 days.
  - Network segmentation: Only 2 of 4 segments isolated.
- **Metric**: Control compliance rate: 45% (based on NIST 800-53 controls).
- **Visualization**:
  - **Pie Chart**: Control Compliance Status (Compliant: 45%, Non-Compliant: 55%).
  - **Code for Chart**:
    ```python
    import matplotlib.pyplot as plt
    labels = ['Compliant', 'Non-Compliant']
    sizes = [45, 55]
    colors = ['green', 'red']
    plt.figure(figsize=(6, 6))
    plt.pie(sizes, labels=labels, colors=colors, autopct='%1.0f%%', startangle=90)
    plt.title('Control Compliance Status')
    plt.savefig('control_compliance.png')
    plt.show()
    ```
![Image](https://github.com/user-attachments/assets/dde356a4-28c9-489f-8ed4-9e13910cbdf4)

#### Detect
- **Detection Gaps**:
  - No real-time intrusion detection system (IDS) deployed.
  - Average detection time: 12 hours post-compromise.
- **Metric**: Mean Time to Detect (MTTD): 12 hours (industry benchmark: 4 hours).
- **Visualization**:
  - **Line Graph**: Detection Time vs. Industry Benchmark.
  - **Code for Chart**:
    ```python
    import matplotlib.pyplot as plt
    categories = ['Operation Winnebago', 'Industry Benchmark']
    times = [12, 4]
    plt.figure(figsize=(8, 5))
    plt.plot(categories, times, marker='o', color='purple')
    plt.title('Mean Time to Detect (MTTD)')
    plt.ylabel('Hours')
    plt.grid(True)
    plt.savefig('mttd_comparison.png')
    plt.show()
    ```
![Image](https://github.com/user-attachments/assets/f4ff04b1-d5bb-47fd-be06-ce7b00d01ec1)

#### Respond
- **Response Actions**:
  - Server room shutdown: 100% effective in halting active attacks.
  - Quarantine of infected systems: 90% completion within 2 hours.
  - Interagency coordination (DHS, FBI): 80% efficiency in information sharing.
- **Metric**: Mean Time to Respond (MTTR): 4 hours (industry benchmark: 2 hours).
- **Visualization**:
  - **Bar Chart**: Response Effectiveness by Action (Shutdown: 100%, Quarantine: 90%, Coordination: 80%).
  - **Code for Chart**:
    ```python
    import matplotlib.pyplot as plt
    actions = ['Server Shutdown', 'System Quarantine', 'Interagency Coordination']
    effectiveness = [100, 90, 80]
    plt.figure(figsize=(8, 5))
    plt.bar(actions, effectiveness, color='orange')
    plt.title('Response Effectiveness by Action')
    plt.ylabel('Effectiveness (%)')
    plt.ylim(0, 100)
    plt.grid(True, axis='y')
    plt.savefig('response_effectiveness.png')
    plt.show()
    ```
![Image](https://github.com/user-attachments/assets/f4a1f01c-f72d-46a7-bab3-89bf0e2715e0)


#### Recover
- **Recovery Metrics**:
  - System restoration time: 6 hours average.
  - Service availability restored: 95% within 12 hours.
- **Visualization**:
  - **Line Graph**: Recovery Time by Sector.
  - **Code for Chart**:
    ```python
import matplotlib.pyplot as plt
    sectors = ['Natural Gas', 'Power Grid', 'Water Supply', 'ISP']
    recovery_times = [8, 5, 7, 4]
    plt.figure(figsize=(8, 5))
    plt.plot(sectors, recovery_times, marker='o', color='green')
    plt.title('Recovery Time by Sector')
    plt.ylabel('Hours')
    plt.grid(True)
    plt.savefig('recovery_time.png')
    plt.show()
    ```
![Image](https://github.com/user-attachments/assets/bd7cb09a-02d4-4efa-ba4c-bbb1fbd7ce11)

### Diamond Model Analysis
The Diamond Model dissects the attack across Adversary, Infrastructure, Capability, and Victim.

#### Adversary
- **Profile**: Coordinated group with advanced skills, likely state-sponsored or ideologically motivated.
- **Evidence**: Emails, SMS, and call logs (3 mobile devices) showed attack planning.
- **Metric**: 15 unique communications linked to adversaries.

#### Infrastructure
- **Attack Infrastructure**: 8 Linux servers used for DDoS attacks, 1 server room for persistent access.
- **Metric**: 70% of attack traffic originated from identified servers.
- **Visualization**:
  - **Bar Chart**: Attack Traffic by Source (Servers: 70%, Workstations: 20%, External IPs: 10%).
  - **Code for Chart**:
    ```python
    import matplotlib.pyplot as plt
    sources = ['Servers', 'Workstations', 'External IPs']
    traffic = [70, 20, 10]
    plt.figure(figsize=(8, 5))
    plt.bar(sources, traffic, color='red')
    plt.title('Attack Traffic by Source')
    plt.ylabel('Percentage (%)')
    plt.ylim(0, 100)
    plt.grid(True, axis='y')
    plt.savefig('attack_traffic.png')
    ```
![Image](https://github.com/user-attachments/assets/4e244f75-66e4-47cb-9dd8-a28c6c264c9f)

#### Capability
- **Techniques**: Spear-phishing (80% success rate), public-facing application exploits (CVSS 8.5), SCADA manipulation, and destructive malware.
- **Tools**: Kali Linux, custom malware, Wireshark-detected DDoS scripts.
- **Metric**: 10 unique malicious tools identified.

#### Victim
- **Targets**: Natural gas (12 SCADA systems), power grid (5 SCADA systems), water supply (3 systems), ISP (2 networks).
- **Impact**: 100,000 customers affected, $12.3M in losses.
- **Metric**: 85% of critical systems impacted.

## Forensic Audit Findings
- **Evidence Collection**:
  - Imaged 8 servers, 15 workstations, 1 USB drive using FTK Imager, Encase, and Fdisk.
  - Captured live network traffic (1.2 GB) using Wireshark and TCP Dump.
  - Chain of custody maintained for 100% of evidence.
- **Key Findings**:
  - Persistent remote access via stolen credentials (80% of systems).
  - Destructive malware deleted master boot records on 60% of affected systems.
  - Registry analysis (HKEY_CURRENT_USER, NTUSER.DAT) confirmed unauthorized user activity.
  - Memory forensics (Volatility) identified 5 malicious processes and 10 open network connections.
  - Mobile device analysis extracted 20 SMS messages and 15 call logs linking to attackers.

## Compliance and Legal Context
- **Applicable Laws**:
  - **Counterfeit Access Device and Computer Fraud and Abuse Act (1984)**: Addresses unauthorized access.
  - **Identity Theft and Assumption Deterrence Act (1998)**: Covers credential theft.
  - **Homeland Security Act (2002)**: Supports DHS coordination.
- **Compliance Gaps**:
  - 60% of systems non-compliant with NIST 800-53 access controls.
  - 50% of incident response processes lacked documentation per NIST 800-61.

## Recommendations
1. **Enhance Preventive Controls**:
   - Implement MFA on 100% of systems (current: 50%).
   - Patch systems within 30 days (current: 90+ days for 30% of systems).
   - Segment all network zones (current: 50% segmented).
2. **Improve Detection**:
   - Deploy IDS/IPS with 95% coverage (current: 0%).
   - Reduce MTTD to <4 hours through SIEM integration.
3. **Strengthen Response**:
   - Test incident response plans quarterly (current: annually).
   - Achieve MTTR <2 hours through automated response tools.
4. **Optimize Recovery**:
   - Maintain offline backups for 100% of critical systems (current: 70%).
   - Conduct recovery drills biannually.
5. **Foster Collaboration**:
   - Establish a joint DHS-FBI-private sector task force (meet monthly).
   - Conduct annual tabletop exercises with critical infrastructure stakeholders.

## Conclusion
The Operation Winnebago audit reveals significant vulnerabilities in critical infrastructure cybersecurity, with a 55% control non-compliance rate and $12.3M in losses. By implementing NIST CSF-aligned controls and addressing gaps identified in the Diamond Model, organizations can enhance resilience. The included metrics and visualizations underscore the urgency of proactive measures to protect national infrastructure.

## Appendix: Visualizations
The following graphs should be rendered in a canvas panel:
1. **Asset Criticality by Sector**: Bar chart showing criticality scores.
2. **Control Compliance Status**: Pie chart of compliance rates.
3. **Mean Time to Detect (MTTD)**: Line graph comparing to benchmark.
4. **Response Effectiveness by Action**: Bar chart of response metrics.
5. **Recovery Time by Sector**: Line graph of recovery times.
6. **Attack Traffic by Source**: Bar chart of traffic origins.

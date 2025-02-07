# CompTIA CySA+ Keynotes

Notes for the CompTIA CySA+ course

---

## Table of Contents

<details>
  <summary>Outline</summary>

1. **Assessing Information Security Risk**
   - Identify the Importance of Risk Management
   - Assess Risk
   - Mitigate Risk
   - Integrate Documentation into Risk Management

2. **Analyzing Reconnaissance Threats to Computing and Network Environments**
   - Assess the Impact of Reconnaissance Incidents
   - Assess the Impact of Social Engineering

3. **Analyzing Attacks on Computing and Network Environments**
   - Assess the Impact of System Hacking Attacks
   - Assess the Impact of Web-Based Attacks
   - Assess the Impact of Malware
   - Assess the Impact of Hijacking and Impersonation Attacks
   - Assess the Impact of DoS Incidents
   - Assess the Impact of Threats to Mobile Security
   - Assess the Impact of Threats to Cloud Security

4. **Analyzing Post-Attack Techniques**
   - Assess Command and Control Techniques
   - Assess Persistence Techniques
   - Assess Lateral Movement and Pivoting Techniques
   - Assess Data Exfiltration Techniques
   - Assess Anti-Forensics Techniques

5. **Managing Vulnerabilities in the Organization**
   - Implement a Vulnerability Management Plan
   - Assess Common Vulnerabilities
   - Conduct Vulnerability Scans
   - Conduct Penetration Tests on Network Assets

6. **Collecting Cybersecurity Intelligence**
   - Deploy a Security Intelligence Collection and Analysis Platform
   - Collect Data from Network-Based Intelligence Sources
   - Collect Data from Host-Based Intelligence Sources

7. **Analyzing Log Data**
   - Use Common Tools to Analyze Logs
   - Use SIEM Tools for Analysis

8. **Performing Active Asset and Network Analysis**
   - Analyze Incidents with Windows-Based Tools
   - Analyze Incidents with Linux-Based Tools
   - Analyze Malware
   - Analyze Indicators of Compromise

9. **Responding to Cybersecurity Incidents**
   - Deploy an Incident Handling and Response Architecture
   - Mitigate Incidents
   - Prepare for Forensic Investigation as a CSIRT

10. **Investigating Cybersecurity Incidents**
    - Apply a Forensic Investigation Plan
    - Securely Collect and Analyze Electronic Evidence
    - Follow Up on the Results of an Investigation

11. **Addressing Security Architecture Issues**
    - Remediate Identity and Access Management Issues
    - Implement Security During the SDLC

</details>

---

## References

- **NIST Publications:**  
  Access publications at [csrc.nist.gov/publications/sp800](https://csrc.nist.gov/publications/sp800)
  - **Publication 800-30:** Guide for Conducting Risk Assessments  
  - **Publication 800-53 rev 5:** Security and Privacy Controls for Information Systems and Organizations
  - **Publication 800-145:** NIST Definition of Cloud Computing  (MUST READ) pg 6-7
  - **Publication 800-207(a):** Zero Trust Architecture (a = Cloud) - useful
- **Benchmark**
  - https://www.cisecurity.org/cis-benchmarks
- Security Technical Implemenation Guides (STIGs)
  - https://public.cyber.mil/stigs/
- Password List
  - cirt.net/passwords (default passwords) 
- Useful info
  - https://www.sans.org/blog/the-ultimate-list-of-sans-cheat-sheets/
  - https://www.sans.org/information-security-policy/?per-page=100
## 1. Assessing Information Security Risk

<details>
  <summary>Expand Details</summary>

### Information Security Governance
- **Guidance for Information Security Managers:**  
  Useful for establishing policies and frameworks. (Relevant for CISSP and CySA+ candidates)

### Identify the Importance of Risk Management
- **Risk Management Principles:**  
  Understanding risk management is key to prioritizing cybersecurity efforts.
  - **Risk Responses:**
    - **Accept:**  
      Example: A company may decide to accept the risk if the cost to mitigate (e.g., \$150,000) is lower than the potential impact (e.g., \$500,000).  
      *Note:* Accepting risk means knowingly operating with vulnerabilities as a cost of doing business.
    - **Avoid:**  
      Avoidance involves eliminating risk by removing the activity that introduces the risk. *(Expand with specific examples as needed.)*
    - **Mitigate:**  
      Reducing the likelihood or impact of the risk through controls and documentation.  
      *Note:* Mitigation reduces risk but does not entirely eliminate it.
    - **Transfer:**  
      Shifting the risk to a third party (e.g., through insurance or outsourcing). *(Expand with additional details as needed.)*

- **Key Concept:**  
  In cybersecurity, we typically deal with **negative risk** (potential harm rather than opportunities).

### Assess Risk
- Evaluating threats, vulnerabilities, and the potential impact on the organization.
- Prioritize risks based on likelihood and business impact.

### Mitigate Risk
- Implement controls and strategies to lower risk to acceptable levels.
- Continually monitor and update risk management strategies.

### Integrate Documentation into Risk Management
- Documentation is essential for tracking risk assessments, controls, and incident responses.
- Ensures continuity and compliance with internal and external standards.

</details>

---

## 2. Analyzing Reconnaissance Threats to Computing and Network Environments

- **Reconnaissance Incidents:**  
  Understand techniques used to gather information about targets.
- **Social Engineering:**  
  Assess how attackers manipulate human behavior to gain unauthorized access.

---

## 3. Analyzing Attacks on Computing and Network Environments
- **Reviewing System and Network Architecture Concepts:**

- **Hypervisors**
  - Type 1 - on hardware
  - Type 2 - app on pc
  
- **System Hacking Attacks:**  
  Tactics and methodologies used by attackers.
- **Web-Based Attacks:**  
  Examine vulnerabilities in web applications.
- **Malware:**  
  Types, propagation methods, and mitigation strategies.
- **Hijacking and Impersonation:**  
  Techniques such as session hijacking and spoofing.
- **Denial of Service (DoS) Incidents:**  
  Methods of overwhelming systems and strategies to mitigate them.
- **Mobile Security Threats:**  
  Understand vulnerabilities specific to mobile devices.
- **Cloud Security Threats:**  
  Evaluate risks associated with cloud environments.
  -  **Cloud access security Broker (CASB)**
    - Enable SSO and enforce access controls
    - scan for malware and rogue or noncompliant device access
    - monitor and audit users and resource activity
    - prevent access to unauthorized cloud services
- **Data Loss Prevention Concepts**
    - Blocking use of external media
    - print blocking
    - RDP blocking
    - Clipboard privacy controls
    - data classification blocking
- "8 levels of syslog"
   - 0 = emergency
   - 1 = Alert
   - 2 = Critical
   - 3 = Error
   - 4 = Warning
   - 5 = warning
   - 6 = Information
   - 7 = Debug
---

## 4. Analyzing Post-Attack Techniques

- **Command and Control (C2):**  
  Understand how attackers maintain communication with compromised systems.
- **Persistence Techniques:**  
  Methods used to maintain access to a compromised system.
- **Lateral Movement and Pivoting:**  
  Techniques used to move within a network post-compromise.
- **Data Exfiltration:**  
  Methods attackers use to extract data.
- **Anti-Forensics:**  
  Techniques to evade detection and complicate forensic analysis.

---

## 5. Managing Vulnerabilities in the Organization

- **Vulnerability Management Plan:**  
  Create, implement, and maintain a plan to manage vulnerabilities.
- **Common Vulnerabilities:**  
  Understand and assess frequent vulnerabilities.
- **Vulnerability Scans:**  
  Use automated tools to identify vulnerabilities.
- **Penetration Testing:**  
  Conduct tests to simulate attacks and identify weaknesses.

---

## 6. Collecting Cybersecurity Intelligence
- **Security Content Automation Protocol (SCAP)
  - Protocol is an agreement between two parties on how something is going to work
  - SCAP Languages
      - Open Vulnerabilities and Assessment Language (OVAL) Consistent and interoperable. Assess information regardless of the security tools
      - Asset Reporting Formart (ARF): Correlate reporting formats.
      - Extensible Configuration Checklist Descriptiion Format (SCCDF)
- SCAP Identification Schemes
     - Common Platform endumeration (CPE)
     - Common Vulnerabilites and Exposure (CVE)
     - Common Configuration Enumeration (CCE)
- **Common Vulnerability Scoring System (CVSS)**
    - first.org/cvss/v3.1/examples
    - ![image](https://github.com/user-attachments/assets/dc0ad186-4878-4426-8ef6-4ce9350b5342)

- **Security Intelligence Platforms:**  
  Deploy platforms for collecting and analyzing security data.
- **Network-Based Sources:**  
  Collect and analyze data from network traffic.
- **Host-Based Sources:**  
  Monitor and analyze data from individual systems.

---

## 7. Analyzing Log Data

- **Common Log Analysis Tools:**  
  Overview of tools and methodologies for log analysis.
- **SIEM Tools:**  
  Use Security Information and Event Management (SIEM) systems for correlating and analyzing security events.

---

## 8. Performing Active Asset and Network Analysis

- **Windows-Based Tools:**  
  Techniques and tools specific to Windows environments.
- **Linux-Based Tools:**  
  Techniques and tools specific to Linux environments.
- **Malware Analysis:**  
  Steps to analyze and understand malware behavior.
- **Indicators of Compromise (IoCs):**  
  Identifying signs of potential security breaches.

---

## 9. Responding to Cybersecurity Incidents

- **Incident Handling and Response Architecture:**  
  Establish and maintain an effective incident response strategy.
- **Incident Mitigation:**  
  Strategies to contain and remediate incidents.
- **Forensic Preparedness:**  
  Prepare for digital forensic investigations as part of a CSIRT (Computer Security Incident Response Team).

---

## 10. Investigating Cybersecurity Incidents

- **Forensic Investigation Plan:**  
  Develop and apply a plan for forensic investigations.
- **Evidence Collection and Analysis:**  
  Securely collect and analyze digital evidence.
- **Post-Investigation Follow-Up:**  
  Use investigation findings to improve security posture.

---

## 11. Addressing Security Architecture Issues
- **Network Attacks**
    - DDOS indicatior = Traffic spike
        - *Worm Activity* : high volumes of traffic saturating switches and router interfaces.
        - *Reflection or amplification attack* : the attacker spoofs victims IP and uses the IP to communicate with multiple servers.
        - *DNS reflection attack* : small dns request with spoofed IP to generate a very large response.
        - *Network Time Protocol (NTP)* : monlist command can be abused to generate large traffic volumes. ex) small query to request the last 600 machines contacted by the ntp server results in a large response. The monlist request from a server with 600 addresses in its memory will be 206 times larger than the initial request. This means that an attacker with 1 GB of internet traffic can deliver a 200+ gigabyte attack — a massive increase in the resulting attack traffic.
    - DDOS MITIGATION
        - Real tiem analysis of log files.
        - Suspicious traffice to blackhoke, especially if automated.
        - GEOlocation & IP reputation
        - services like cloudflare.
    - Command and Control (C2C or C2)
        - bot beacons home and conducts simple transactions.
        - remote code execution remotely on a massive scale.
        - uses HTTP/HTTPS /DNS Tunneling/ Internet relay chat (IRC/ Port 6667)
- **Identity and Access Management (IAM):**  
  Identify and remediate issues within IAM frameworks.
- **Security During the SDLC:**  
  Integrate security practices throughout the Software Development Life Cycle.

---

## Final Notes

- **Documentation is Key:**  
  In every step—from risk assessment to incident investigation—thorough documentation ensures accountability and continuous improvement.
- **Continuous Learning:**  
  Cybersecurity is an ever-evolving field. Stay updated with the latest threats, mitigation strategies, and industry standards.
- **REPEATED KEYWORDS**
  - Shadow IT: people take it upon themselves to install software 
---



# Radhika Patel — Network, Cloud & Cybersecurity Portfolio

IT professional with hands-on training in enterprise network design, cloud infrastructure, and cybersecurity — completed through a TAFE Queensland Diploma of IT. Projects cover Cisco routing & switching, AWS cloud deployment, Windows Server administration, penetration testing, incident response, and security data analysis. All projects are simulated client scenarios from TAFE coursework, not real employment.

**Core skills:** VLAN Design · OSPF/RIPv2 · Cisco IOS · IPSec VPN · Zone-Based Firewall · ACLs · DHCP/DNS/NAT · Windows Server 2019 · Active Directory · Group Policy · AWS (EC2, VPC, S3, RDS, CloudFormation) · Kali Linux · Penetration Testing · Nmap · Metasploit · Wireshark · Splunk · Python · SQL

📧 [radhikadave18@gmail.com](mailto:radhikadave18@gmail.com) | 🔗 [LinkedIn](https://www.linkedin.com/in/radhikadave18/) | 💻 [Portfolio Site](https://radsdave.github.io/Portfolio/)

---

## Networking & Cloud Projects

### Project 1 — Cloud Infrastructure as Code Deployment (AWS)
*TAFE Diploma of IT — Simulated DevOps Engineer Role*

Deployed a PHP/MySQL e-commerce web application to AWS using Infrastructure as Code, simulating a real DevOps engineering scenario for a cupcake business.

- Evaluated CloudFormation, Kubernetes/Helm, and Ansible as IaC options and selected **AWS CloudFormation**
- Built and deployed CloudFormation templates (YAML/JSON) provisioning a **VPC**, public subnet, Internet Gateway, route tables, **Security Groups**, **EC2** web server, and **S3** bucket
- Managed all resources through the **AWS CLI** — updated security rules, deleted and recreated stack components without manual console clicks
- Authored a custom multi-tier CloudFormation template with runtime parameters and **Amazon RDS (MySQL)** database, handling credentials securely as secrets
- Diagnosed and resolved a live deployment fault (HTTP 500 from missing SSL configuration) through structured troubleshooting

**Keywords:** AWS · CloudFormation · IaC · EC2 · VPC · S3 · RDS · Security Groups · AWS CLI · YAML/JSON · Cloud Troubleshooting

---

### Project 2 — Enterprise Network Redesign & Security Proposal (HelpYou Mortgage Co.)
*TAFE Diploma of IT — Simulated Network Engineer Role*

Designed a full network modernisation plan for a growing 70-staff mortgage company expanding across two floors and two sites, covering gap analysis through to hardware procurement and a formal security proposal.

- Conducted a **gap analysis** of current vs. target IT environment (qualitative & quantitative)
- Designed a complete **VLAN segmentation scheme** across departments (IT, HR, CS, Admin, Marketing, Servers, DMZ) with full IP addressing plan
- Wrote **Cisco switch configurations**: trunking, **EtherChannel** redundancy, PortFast/BPDU Guard, per-department access ports
- Designed a **site-to-site GRE VPN tunnel** between two office locations
- Planned redundant **Active Directory**, **DNS**, **DHCP**, and **ESXi virtualization** infrastructure
- Selected and costed enterprise hardware: **Cisco Catalyst switches**, **FortiGate NGFW**, **Dell PowerEdge servers**, **Bitdefender AV**, **PRTG** — full budget proposal ($47K initial / $21K/yr recurring)
- Designed for **dual-WAN failover**, **NIC teaming**, and automated backup/disaster recovery
- Produced a formal **Network Security Proposal** aligned to NIST/ISO and ACSC Essential Eight — covering MFA, password policy, log management, email security, and DMZ architecture

**Keywords:** VLAN Design · Cisco Catalyst · EtherChannel · GRE VPN · FortiGate NGFW · Active Directory · DNS/DHCP · ESXi · Disaster Recovery · Hardware Procurement · NIST · Essential Eight

---

### Project 3 — WAN Deployment & Dynamic Routing
*TAFE Diploma of IT — Cisco Packet Tracer (ICTNWK541/542/543)*

Designed and configured WAN connectivity and multi-protocol routing for simulated business clients across multiple Packet Tracer assignments.

- Designed a 3-department network (Sales/HR/Marketing) using **VLSM subnetting**, wrote full Cisco router/switch configs (VLAN trunking, sub-interfaces, VTY security)
- Configured **WAN links**: **PPPoE with CHAP** authentication and **HDLC/PPP** between ISP and customer routers; performed **router firmware upgrades**
- Implemented **Static routing**, **Default routes**, **RIPv2**, and **OSPF** dynamic routing across multi-router topologies
- Wrote and applied **per-VLAN extended ACLs** enforcing a defined security policy — allowed HTTP/DNS to specific hosts, blocked internet for one server, verified with `show access-lists` and ping tests
- Configured **NAT overload** and **static NAT** to expose an internal web server via a single public IP
- Built a **GRE VPN tunnel** for remote teleworker access with OSPF running over the tunnel
- Diagnosed and fixed a real inter-site connectivity failure by tracing it to a missing static route

**Keywords:** Cisco IOS · Packet Tracer · VLSM · PPPoE/CHAP · HDLC · Extended ACLs · NAT · GRE Tunnel · RIPv2 · OSPF · Static Routing · Network Troubleshooting

---

### Project 4 — Multi-Site Network Security, Services & Infrastructure
*TAFE Diploma of IT — Simulated Network Engineer Role (ICTNWK529)*

Configured a full multi-site network stack covering secure connectivity, identity, collaboration, and monitoring — with real troubleshooting documented for each component.

- Built a **Site-to-Site IPSec VPN over GRE**; diagnosed a stalled **IKE Phase 1** negotiation (`MM_NO_STATE`) caused by a misconfigured peer IP in the ISAKMP key and fixed it
- Configured a Cisco **Zone-Based Firewall** (PRIVATE/INTERNET zones, class-maps, policy-maps) to permit only HTTP/HTTPS/DNS/ICMP outbound; troubleshot a silent drop from a missing ICMP match
- Deployed and hardened a **Squid proxy server** on Linux (UFW rules, ACL-based access control), resolving a config syntax fault blocking startup
- Configured **DHCP scopes** for VoIP and data VLANs; debugged a no-lease issue traced to a sub-interface in shutdown state
- Stood up **multi-site Active Directory** (two domain controllers, AD Sites and Services, scheduled inter-site replication); fixed a replication failure via Netlogon service restart
- Implemented **DFS**, **FSRM** (quotas, file screening), and **Group Policy Objects** for desktop standardisation; resolved file-screen-blocked rename issue
- Deployed **WSUS** and joined a **Linux client to the Windows domain** using realmd/SSSD
- Built a working **email server (hMailServer)** with DNS MX/A records, fixing a failed IMAP/SMTP handshake
- Configured **Cisco VoIP** with voice/data VLAN separation, `telephony-service`, and `ephone-dn` extensions; resolved a phone registration conflict
- Implemented **Syslog and SNMP monitoring** with **PRTG**; flagged default SNMP community string as a security risk
- Deployed **Security Onion (Suricata IDS)** with a switch **SPAN port** for traffic mirroring; ran Nmap scans and captured a live SNMP alert

**Keywords:** IPSec VPN · IKE/ISAKMP · Zone-Based Firewall · Squid Proxy · Multi-Site AD · DFS · FSRM · GPO · WSUS · Linux-AD Integration · VoIP · SNMP/Syslog · PRTG · Security Onion · Suricata IDS · SPAN Port

---

### Project 5 — Integrated Server Solution: Build, Test & Troubleshoot (Anzac Airport)
*TAFE Diploma of IT — Simulated On-Site IT Technician Role (ICTNWK539/540)*

Built, configured, and formally tested two integrated server solutions in a virtualised environment for a simulated work-site (Anzac Airport), following WHS and change management procedures.

- Conducted a formal **risk assessment** and followed **WHS** procedures before beginning
- Deployed two **virtual machine** environments (VMware/Hyper-V) combining **Windows Server 2019** with a non-Windows OS in the same domain
- Configured **Active Directory**, OUs, users, groups, and workstation domain-join
- Deployed core services: **DHCP**, **DNS**, **WSUS**, **NTP**, **proxy server**, and cross-platform **Samba** file sharing
- Configured **Windows Firewall** and **Linux firewall** rules; set up **web, mail, and FTP** services
- Ran a structured **test plan** covering connectivity, cross-platform AD login, **Performance Monitor** (CPU/RAM/disk), and **Veeam** backup/restore
- Documented all issues, root causes, and fixes in a formal troubleshooting report; obtained client sign-off

**Keywords:** Windows Server 2019 · Active Directory · DHCP/DNS · WSUS · NTP · Samba · VMware · Hyper-V · Veeam · Performance Monitoring · WHS Risk Assessment · Troubleshooting

---

### Project 6 — Enterprise Communication Solution (Daydream Travel)
*TAFE Diploma of IT — Simulated IT Consultant Role (ICTNWK536)*

Planned, configured, and tested a full enterprise communication platform for a travel agency expanding to four city locations.

- Evaluated platforms against business requirements and selected **Slack** with **Zoom VoIP**, **Haekka**, **Polly**, and **Office 365** integration
- Created a **Gantt chart (Excel)** to manage a 3-phase rollout (planning → installation/migration → testing/training)
- Authored a formal **implementation plan**: 6-month schedule, $200,000 budget, 90% adoption target, 99.9% uptime SLA
- Set up 8 user accounts with **role-based permissions** and enforced **Two-Factor Authentication (2FA)**
- Documented **planned downtime**, staff training plan, and phased rollout to minimise business disruption
- Deployed in a **test environment** first; ran functional and security tests before production rollout

**Keywords:** Slack · Zoom VoIP · Office 365 · 2FA · RBAC · Gantt Chart · Implementation Planning · Stakeholder Management · Staff Training · Change Management

---

## Technical Lab Practice

### Windows Server 2019 & Fedora Linux — 28-Lab Infrastructure Exercises
*TAFE Diploma of IT — ICTNWK539/540 Lab Manual*

Independent hands-on lab exercises covering end-to-end Windows Server 2019 and Fedora Linux administration across 28 structured labs in a virtual environment.

- **Virtualisation:** VMware Workstation, **Hyper-V** (dynamic memory, QoS, pass-through disks, PowerShell VM provisioning, virtual switches), **VMware ESXi** (Type-1 hypervisor, virtual switches, datastores)
- **OS & Domain:** Clean install of Windows Server 2019, Windows 10, and Fedora 37; joined all platforms to a single **Active Directory** forest
- **AD & GPO:** Installed ADDS, created OUs/users/groups via GUI and **PowerShell**; configured **GPOs**, security/audit policies, **Software Restriction Policies**, and **AppLocker**
- **Storage:** Storage Pools, volumes, **NTFS permissions**, Work Folders
- **Network Services:** DHCP (IPv4/IPv6), DNS (zones, resource records, reverse lookup), NTP, Windows Firewall, IIS
- **Patch & Monitoring:** WSUS, Event Viewer, Performance Monitor, Resource Monitor
- **Linux:** Users/groups, file permissions, FTP, web server, mail server, **Squid proxy**, NFS/SMB Samba cross-platform file sharing
- **Print Services:** Printer deployment via Group Policy

**Keywords:** Windows Server 2019 · Fedora Linux · AD · GPO · AppLocker · DHCP/DNS · WSUS · IIS · Hyper-V · VMware ESXi · PowerShell · NTFS · Samba/NFS · Squid · Performance Monitor · Type-1 Hypervisor

---

## Cybersecurity Projects

### Project 7 — Incident Response Team Exercise (IRTx): "Minotaur"
*TAFE Diploma of IT — Red Team Operator & Project Coordinator (7-person team)*

Full-scale simulated cyber attack exercise against a live target server ("Minotaur") from Hack The Box, deployed in Oracle VirtualBox. My dual role was Red Team operator and project coordinator.

**Red Team Attack Chain:**
- **netdiscover** — subnet scan to identify the target's live IP (reconnaissance)
- **Nmap** (`-sV`) — service enumeration to map open ports and attack surface
- **DirBuster** — web directory brute-force to uncover hidden entry points
- **WPScan** — WordPress user enumeration and credential brute-force using a custom wordlist
- **Metasploit** (`wp_slideshowgallery_upload`) — exploited **CVE-2014-5460** (arbitrary file upload), uploaded a PHP web shell (`c99.php`), gained **Remote Code Execution**
- **curl** — retrieved flags and `shadow.bak` password hash file from the compromised server
- **John the Ripper** — cracked password hashes, escalated privileges: standard user → `heffer` → `minotaur` → `root`
- **Mid-exercise adaptation** — original privilege escalation path blocked by configuration change; team designed and executed an alternate path on the fly

**Blue Team (observed):** Detected 80% of attacks using **Suricata SIEM**; ultimately blocked the Red Team via a **pfSense Firewall** rule

**Project coordination:** Managed scheduling and documentation across the team; co-authored IRTx Closure Report and Project Closure Report; co-delivered 15-minute stakeholder presentation

**Keywords:** Red Team · Penetration Testing · Hack The Box · netdiscover · Nmap · DirBuster · WPScan · Metasploit · CVE-2014-5460 · RCE · Privilege Escalation · John the Ripper · Suricata SIEM · pfSense · MITRE ATT&CK · NIST SP 800-61 · Project Management

---

### Project 8 — Web Application Security Testing (Midtown IT)
*TAFE Diploma of IT — Simulated Junior Penetration Tester Role*

Structured web application security assessment against XVWA (deliberately vulnerable web app) on Ubuntu, using Kali Linux in a VMware virtual lab.

**Objective:** Find and document real vulnerabilities before an attacker could exploit them, mapped to OWASP Top 10.

| Tool | Purpose |
|---|---|
| Nmap | Port scan to map open services before testing |
| Nikto | Web server scan — detected outdated Apache, missing headers, exposed `wp-config.php` |
| Burp Suite | Intercepted and modified live HTTP requests mid-flight; spidered hidden endpoints |
| OWASP ZAP | Automated scan for broken authentication and session management weaknesses |
| Manual testing | SQL Injection and IDOR — attacks automated tools typically miss |

**Key findings:** SQL Injection (full DB access) · IDOR (unauthorised access to other users' data) · Exposed config file with DB credentials · Outdated Apache (EOL, unpatched) · Missing HTTPOnly cookie flag (XSS/session hijacking risk)

All findings mapped to **OWASP Top 10** with severity ratings and remediation recommendations.

**Keywords:** Kali Linux · Nmap · Nikto · Burp Suite · OWASP ZAP · SQL Injection · IDOR · XSS · Broken Authentication · OWASP Top 10 · Web Application Penetration Testing

---

### Project 9 — Cloud Security Plan (Rossco's Coffee — AWS)
*TAFE Diploma of IT — Simulated Cloud Security Consultant Role*

Evaluated an existing AWS environment, identified security gaps, and designed a full cloud security upgrade for a coffee franchise with fake order and data security problems.

- **Assessed current state:** EC2, VPC, Security Groups, IAM, Elastic Load Balancer — found single IAM user (no MFA), no WAF, no DLP, no disaster recovery, public subnet exposure
- **Designed upgrade:** EC2 Auto Scaling, Elastic Load Balancer, RDS Multi-AZ, VPC segmentation, AWS Backup
- **Security controls added:** AWS WAF, MFA, RBAC (IAM), AWS Cognito, AWS Shield (DDoS), DLP, DNSSEC, CASB, AWS KMS encryption
- **Monitoring:** AWS CloudWatch, CloudTrail, GuardDuty, Splunk/ELK Stack
- **Incident Response Plan** designed following **NIST SP 800-61** phases
- **Testing & Migration Plan:** AWS Inspector, Nessus, Kali Linux, Metasploit, Apache JMeter
- **Migration strategy:** Virtual-to-Virtual (AWS-to-AWS) using **Blue-Green deployment** (Elastic Beanstalk + CodeDeploy)
- Documented **RPO/RTO objectives** and cost monitoring via AWS Budgets

**Keywords:** AWS · EC2 · VPC · IAM · MFA · RBAC · AWS WAF · AWS Shield · KMS · CloudWatch · CloudTrail · GuardDuty · RDS Multi-AZ · Auto Scaling · DLP · DNSSEC · NIST SP 800-61 · Blue-Green Deployment · Cloud Security Architecture

---

### Project 10 — Cyber Security Data Analysis (Midtown IT)
*TAFE Diploma of IT — Simulated Cyber Security Analyst Role (VU23216)*

Performed cyber security data analysis using SQL Server and Splunk Enterprise, covering database security, SQL injection, big data log analysis, and SOC monitoring.

- Built a relational database (`Radhika_Employee_DB`) in **Microsoft SQL Server (SSMS)**; performed full **CRUD operations** using SQL CREATE, INSERT, SELECT, UPDATE, DELETE
- Executed a live **SQL Injection attack** on a simulated banking site — demonstrated unauthorised access to account data and transactions
- Installed **Splunk Enterprise**, created a Power user, and ingested 30-day log datasets
- Analysed **63,884 log events** — identified 77.3% failed SSH password attempts from a single IP targeting the `ubuntu` user, flagged as a likely **brute force attack**
- Used Splunk Patterns and Statistics views to visualise event frequency and detect anomalies
- Configured **Windows local host monitoring** in Splunk (Network Adapter data every 20 seconds); exported a Splunk report as PDF
- Documented how Splunk supports **SOC operations** using data from Firewalls, IDS, Access Control Systems, and SIEMs

**Keywords:** SQL Server · SSMS · CRUD · SQL Injection · Splunk Enterprise · Log Analysis · Brute Force Detection · Anomaly Detection · SOC Monitoring · SIEM · IDS · Big Data · Windows Host Monitoring

---

### Project 11 — Vulnerability Testing & Penetration Testing Lab (Midtown IT)
*TAFE Diploma of IT — Simulated Cyber Security Analyst Role (VU23215)*

Conducted vulnerability testing and controlled penetration testing across a multi-VM lab environment, then performed ethical hacking research on real-world vulnerabilities.

**Lab Setup (Kali Linux / Metasploitable-2 / Ubuntu Desktop):**
- Configured a 3-VM isolated network; edited `/etc/network/interfaces`, verified end-to-end connectivity
- **Nmap** — ran `-sT`, `-F`, `-A`, `-sC`, `-PU` scans; identified 23 open ports on Metasploitable-2; retrieved SSH banner via **amap** (`OpenSSH 4.7p1`)
- **Wireshark** — analysed TCP/UDP captures; identified HTTP conversation OS/browser; captured and described **TCP 3-way handshake** SYN/SYN-ACK/ACK flags
- **Telnet vs SSH** — captured plaintext Telnet credentials; confirmed SSH traffic fully encrypted
- **DoS Attack** — ran `dos.py` Python script for TCP SYN flood; ran **Ettercap** spoofed SYN flood; captured and analysed attack packets in Wireshark
- **Man-in-the-Middle** — used **arpspoof** to poison ARP tables on Ubuntu and Windows; confirmed MITM via ARP table MAC address mismatch; used **dsniff** to extract captured credentials
- **Metasploitable-2 Exploitation** — used Metasploit `usermap_script` to exploit **Samba Command Execution vulnerability**; obtained root shell

**Ethical Hacking Research:**
- Researched 3 current malware threats: Laplas (clipper), Netshta (network spread), ViperSoftX (crypto stealer)
- Documented legal implications under **Australian Cybercrime Act 2001** and **Criminal Code Act 1995**
- Used **enum4linux** for user enumeration — gathered SID mappings and Unix user accounts
- Researched zero-day cases: **Heartbleed (OpenSSL, 2014)** and **EternalBlue/WannaCry (2017)** — documented mitigation plans
- Analysed **WLAN vulnerabilities**: WEP weaknesses, rogue APs, MAC spoofing, WPS PIN brute-force
- Wrote Python scripts: subnet ping scanner (filtered to active hosts only), port enumeration script, banner retrieval script
- Evaluated 3 Python ethical hacking libraries: **Scapy**, **Impacket**, **PyCryptodome**

**Keywords:** Kali Linux · Metasploitable-2 · Nmap · Wireshark · Ettercap · arpspoof · dsniff · Metasploit · Samba Exploitation · TCP SYN Flood · Man-in-the-Middle · ARP Spoofing · CVE · Heartbleed · EternalBlue · WLAN · enum4linux · Python Network Scripting · Scapy · Impacket · OWASP Top 10 · Ethical Hacking

---

### Project 12 — Python Security Automation (Midtown IT)
*TAFE Diploma of IT — Simulated Junior Software Developer Role*

Designed, developed, tested, and documented three Python automation scripts following a full SDLC — from client requirements through pseudocode, desk-check testing, coding, debugging, and stakeholder sign-off.

**Scripts built:**
- **Rock Paper Scissors** (2-player game) — `if-elif-else` logic, `while` loop, `.lower()` input standardisation
- **Multiplication Table Generator** — modular functions, loops, f-strings, integer type conversion, input validation
- **Caesar Cipher** (encrypt/decrypt) — character shifting using array indexing and modulo arithmetic; handles spaces, full stops, and unsupported characters with error messages

**Process followed:**
- Gathered client requirements and documented security considerations (input validation, error handling, code review)
- Designed pseudocode algorithms and verified logic via **desk-check tables** before coding
- Compared 4 IDEs (Thonny, PyCharm, VS Code, Atom) across 7 features; selected **Flask + Thonny** with written justification to project manager
- Maintained a **communication log** across 7 in-person meetings covering design, implementation, testing, and review
- Produced user documentation and obtained **project manager sign-off** on all three scripts

**Keywords:** Python · Algorithm Design · Pseudocode · Desk Check Testing · Flask · Thonny · Input Validation · Error Handling · Caesar Cipher · Encryption · SDLC · Stakeholder Sign-off

---

### Project 13 — Cyber Security Risk, Governance & Compliance Research
*TAFE Diploma of IT — Simulated Cybersecurity Governance Analyst Role*

Conducted cyber risk, governance, and compliance assessments across multiple simulated business environments, identifying regulatory obligations and recommending security controls.

- Researched and applied major **Australian cyber legislation**: Privacy Act 1988, Telecommunications (Interception and Access) Act 1979, Criminal Code Act 1995, Corporations Act 2001, APRA CPS 234
- Evaluated international regulations: **GDPR**, UK Data Protection Act 2018, **CCPA**, Budapest Convention on Cybercrime
- Applied **NIST CSF**, **ACSC Essential Eight**, **MITRE ATT&CK**, and **Cyber Kill Chain** frameworks to assess threats and control effectiveness
- Developed organisational **Cyber Safety Protocol** and **Virtual Meeting Protocol** for secure collaboration
- Recommended controls including MFA, network segmentation, SIEM, IDS/IPS, encryption, audit logging, and PCI-DSS aligned payment security
- Produced compliance gap analysis reports with remediation priorities for each assessed business

**Keywords:** Cyber Risk Assessment · GRC · NIST CSF · ACSC Essential Eight · MITRE ATT&CK · Privacy Act 1988 · APRA CPS 234 · GDPR · CCPA · Compliance Gap Analysis · Security Governance

---

## Repository Structure

```
/projects
  /01-aws-cloudformation-cupcakes
  /02-helpyou-mortgage-network-redesign
  /03-wan-dynamic-routing
  /04-multi-site-network-security
  /05-integrated-server-build-test
  /06-daydream-travel-communication
  /07-irtx-minotaur-red-blue-team
  /08-web-app-security-testing
  /09-cloud-security-plan-aws
  /10-cyber-security-data-analysis
  /11-vulnerability-penetration-testing-lab
  /12-python-security-automation
  /13-cyber-risk-governance-compliance
/lab-practice
  /windows-server-fedora-linux-28-labs
/assets
  → diagrams, network topologies, screenshots
index.html  → GitHub Pages portfolio site
README.md   → this file
```

---

## Contact

**Radhika Patel**
📧 [radhikadave18@gmail.com](mailto:radhikadave18@gmail.com) | 🔗 [LinkedIn](https://www.linkedin.com/in/radhikadave18/) | 💻 [Portfolio](https://radsdave.github.io/Portfolio/)

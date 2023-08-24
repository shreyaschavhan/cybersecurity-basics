## 𝐁𝐚𝐬𝐢𝐜𝐬 𝐨𝐟 𝐂𝐲𝐛𝐞𝐫𝐒𝐞𝐜𝐮𝐫𝐢𝐭𝐲 - 𝐓𝐡𝐢𝐧𝐠𝐬 𝐘𝐨𝐮 𝐒𝐡𝐨𝐮𝐥𝐝 𝐊𝐧𝐨𝐰 𝐁𝐮𝐭 𝐍𝐨𝐭 𝐍𝐞𝐜𝐞𝐬𝐬𝐚𝐫𝐢𝐥𝐲

- The CIA Triad
> - 3 pillars (maybe four?) of cybersecurity. 

```
- CIA stands for:
   - C - Confidentiality : Unauthorized Individuals should not access the data. 
   - I - Integrity : Unauthorized Individuals should not modify the data.
   - A - Availability : The system should be available to its users.
```

> - Non-repudiation: Not in CIA but should be considered - It means one should not be able to falsely deny that they created, altered, or has something to do with that data.

---

- The 5 Functions.
> - It's developed to provide organizations with a framework to establish a systematic approach to manage and improve their security posture.
```
- Identify : Understanding what needs protection.
- Protect : Applying security controls, policies, and safeguards to mitigate the identified issues.
- Detect : Quickly identifying any potential breaches, anomalies, or suspicious activities.
- Respond : Steps to take in response in case of a cybersecurity incident.
- Recover : Recovering to normal operations as quickly as possible.
```

---

- A Few Security Roles:
> - Not that IMP but good to know.
```
- CISO : Lead person responsible for security in organization
- ISSO : Responsible for securing data
```



--- 

- Security Controls: 
> - Measures to ensure security across the organization.
> - Types: Depending on how we implement them
```
- Technical - Hardware and Software
- Operational - Human factor
- Manegerial - High Level Guidance
```
> - Types: Depending on their goals.
```
- Preventitive - stops attack or prevent it.
- Detective - Record, log, inform, alert or detect the attack
- Corrective - recover from attack
- Deterrent - discourages human attackers
- Compensating - "at least we have this"
- physical - light, camera, doors, etc
```

---

- Popular Standards and Regulations
```
- GDPR - General Data Protection Regulation for European Contries.
- GLBA - Gramm-Leach-Bliley Act for financial services.
- SOX - Sarbanes–Oxley Act for financial services in US.
- CSA - Computer Security Act
- FISMA - Fedaral Information Security Management Act
- HIPPA -  Health Insurance Portability and Accountability Act
- CCPA - California Consumer Privacy Act
- PCI DSS - Payment Card Industry Data Security Standard
```

--- 

- Vulnerability
> - Vulnerability is anything (any sort of weakness) that helps the attacker in attacking or exploiting our system to cause a negative impact.

---

- Threat
> - Threat is the potential of that vulnerability to exploit our system to cause an impact. And how likely that the vulnerability will be exploited.

--- 

- Risk
> - Risk = Vulnerability + Threat

---

- APT - Advanced Persistent Threat
> - This type of attacks are persistent in nature, meaning the hacker can not only exploit the system but can also maintain persistent access to it, also covering the tracks of the attack.

--- 

- Attack Surface
> - How much exposed you are to attack. How many inputs the attacker can tamper with in order to try to gain access to the system.

---

- Attack vector

> - Point of entry by which an attack can happen is known as attack vector.
> - Common attack vectors:

```
- Email
- Removable media
- Wireless
- Websites
- Social Media
- Instant Messaging platform
- Local workstation access
- Cloud
- Supply Chain
```

---

- Threat Intelligence:
> - It refers to the information and knowledge collected about potential cyber threats, like viruses, trojans, hackers, or other malicious activities.

---

- Threat Modeling:
> - It's like creating a map of all possible threats for a system.

---

- Network Recon:
> - It's a process of gathering information about a target network, it's devices, services, and configurations.
> - Basic tools:

```
- ipconfig / ifconfig /ip
- ping
- arp
- route
- traceroute / trace / tracert
- mtr
- pathping
- Nmap: Network Mapper
> - Network Sweep : we can do this using ping too
> - Service discovery
> - Version detection
> - OS footprinting
- netstat
- theHarvester
- curl
- nessus
- scanless

```

- DNS Recon:
> - It's kind of Network recon but more specific in nature and focuses on DNS.
> - DNS recon involves querying DNS servers and records to collect valuable information about a target's domain names and network infrastructure
> - Basic DNS Recon Tools
```
- nslookup
- dig
- host
- dnsenum
```

- Packet Capture and Analysis
> - This also comes under network recon.
> - It's kind of a technique that invovles capturing and examining network packets to understand and troubleshoot network activity, diagnose issues, monitor performance, and identify security threats.
> - Tools:
```
- tcpdump
- wireshark
```

- Packet Injection
> - Technique to send custom crafted packets.
> - Tools:
```
- hping
- scapy
- tcpreplay
```

```
Detailed Notes Here: https://github.com/shreyaschavhan/network-recon
```

---

- 0-day
> - Vulnerability that doesn't have any existing patch yet.

---

- Social Engineering
> - Hacking the Human in short.
> - Techniques:
```
- impersonation
- Dumpster Diving
- Tailgating
- Piggybacking
- Shoulder surfing
- "Lunchtime" attacks
- phishing
- Vishing
- SMiShing
- Pharming
- Typosquatting
- "Watering hole"
```
---

- Malware
> - Types by infection vector:
```
- Viruses: Viruses are malware that victim has to interact with and trigger it's execution.
- Worms: Worms executes automatically and doesn't require user interaction.
- Trojans: They appear to be good software but they contains additional malicious code.
- Grayware: bloatware, unwanted preinstalled softwares. They don't do malicious by default but theya are annoying.
```

- Virus Types:
```
- file-based
- memory-based
- boot-sector based
- script or macro-based
- multipartite viruses
```

- Shellcode:
> - small piece of executable code that can be passsed in web requests/replies, does not need a physical file on the disk.

- Spyware:
> - Software that monitor activity of user/host.

- Keyloggers:
> - It catches key strokes that you type.

- Adware:
> - Software sponsored by ads.

- Backdoors:
> - Ensure a hacker's remote access to a compromised system.
> - Also known as RATs (Remote Access Trojans)

- Botnet:
> - Command and control network malwares.

- Rootkit:
> - Executed with root/system privileges.

- Ransomware/CryptoLocker:
> - Encrypt data, ask you for ransom in exchange of decryption key.
> - Have backup of all files.

- Crypto-malware:
> - Use your resources to mine crypto currency.

- Logic Bomb:
> - Schedule itself to be able to execute if some condition is met.

- Detecting Malwares:
```
- Anti-virus/malware solutions.
- Sandbox execution and monitoring.
- Resource Monitoring.
- File system monitoring (Tripwire).
- Network Traffic analysis.
- Process Analysis.
-  
```
---

- Cryptography
> I had an entire subject on this in 3rd year.

- Digital Signatures
> - Digital Signatures: hashing + encryption
> - Basically it's just an encrypted hash.

- Digital Envelope
> - Provides secure data container to protect the entire message.

---

- Identity and Access Management (IAM)
> - Triple A - AAA
```
- (Identification)
- Authentication (AuthN)
- Authorization (AuthZ)
- Accounting
```

- Authentication in Computer Systems
> - Knowledge based
> - Kerberos: Active Directory Authentication and authorization system.
```
KDC: Key Distribution Center
AS: Authentication Service
TGT: Ticket Granting Ticket
TGS: Ticket Granting Service
```
> - PAP: Password Authentication Protocol
> - CHAP: Challenge Handshake Authentication Protocol

- Authentication Technologies and Key Management
```
- Smart cards
- USB Keys
- TPM chips (Trusted Platform Modules)
- HSM (Hardware Security Module)
```

- Types of Accounts:
> - Generic Users - less privilege
> - Guest accounts - LEAST privilege / anonymous login
> - Administrator - highest privilege
> - Shared account - shared privilege
> - Generic admin accounts - built in default accounts

---


- Network Devices:
```
> - Switches & Access points
> - Routers
> - Firewalls
> - Load balancers
```




## To learn more about (in-tray):

- Zonetransfer

## To make notes on (in-tray):

- Here: https://github.com/shreyaschavhan/network-recon
   - Network recon tools
   - DNS recon tools

---

- `Footnotes`: 
> - [CompTIA Security+ Full Course on Youtube](https://youtube.com/playlist?list=PLMYSjEaGLw_uut80YG0zyLsrPJ94Y8LU9)
> - Random Google Searches + ChatGPT


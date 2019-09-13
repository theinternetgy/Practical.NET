# Understanding Ethical Hacking
- Information Security
- Technology Triangle
- Security Threats
- Attack Vectors
- Hacking Concepts
- Hacking Phases
- Attack Types

# Reconnaissance/Footprinting
- Looking for basic information
  + websites
  + whois
  + ping
  + nslookup
  + tracert
  + email
  + Netcraft
- Social Networking Sites
- Job Sites
- Search Engines
  + Google Hacking
  + Google Hacking Database
  + Google Hacking Tools
- Countermeasures & Pen Testing

# Scanning Networks
- TCP Communications
- UDP Communications
- TCP Header Flags
- TCP 3-Way Handshake
- Scanning Tools:
  + Angry IP
  + Nmap/Zenmap
  + hping3
  + Firewalk
  + Fing - Network Tools (Adroid)
- Types of Scanning:
  + Full Scans
  + Half-open Scans
  + Xmas Scans
  + FIN Scans
  + NULL Scans
  + UDP Scans
  + Evading IDS Systems with Idle Scans
  + Listing and SSDP (Simple Service Discovery Protocol) Scanning
- Countermeasures:
  + Firewalls configured to look for SYN Scans
  + IDS (Intrusion Detection System) should dectect Nmap/Snort
  + Open only require ports
  + Filter ICMP messages
  + Test your own network
  + Keep firewalls/ IDS updated/patched
- IDS Evasion Methods:
  + Spoof your IP and sniff the responses (nmap -D, nmap -sI)
  + Use a proxy or pwned machine
  + Fragment IP Packets (nmap -f)
  + If you're able, use source routing
- OS Fingerprinting:
  + nmap -O
- Banner Grabbing: information is leaked by default messages
  + telnet
  + netcap
- OS Fingerprinting & Banner Grabbing Countermeasures:
  + Misdirection/ fake banners
  + IIS lockdown tool
  + ServerMask
  + Turn off unused services
  + Change the ServerSignature (httpd.conf, httpd.config: mod_headers)
  
# Enumeration
- Defaults & NetBIOS (Network Basic Input/Output System)
  + Change it
  + Be aware of your ports
  + Turn off SMB
- SNMP (Simple Network Management Protocol)
  + Turn it off
  + Upgrade to v3
  + Group policy: "additional restrictions for anonymous connections"
  + Block ports 161 on TCP/UDP
  + IPSec filtering
  + Limit access to null sessions
- LDAP (Lightweight Directory Access Protocol)
  + Separate email address and logon names
  + Use SSL to encrypt LDAP
  + Encrypt drives that store LDAP databases
- NTP (Network Time Protocol)
  + Watch your ports
  + Understand what software is installed
  + Check your master NTP
- SMTP (Simple Mail Transfer Protocol)
  + Disable open relays
  + Drop unknown recipients
  + Never include email server info in your email or posts
- DNS (Domain Name System)
  + Configure DNS Zone Transfer to explicit servers
  + Ensure that nonpublic hostnames are not referenced to IP with the DNS Zone files or publicly accessible DNS servers
  + Check both internal and external DNS servers
  + Ensure that HINFO and other records do not appear in DNS zone files
- IPSec (Internet Protocol Security)
  + nmap -sU -p 500 <targetIP>
  + ike-scan -M <targetIP>
- VoIP (Voice over Internet Protocol)
  + SIP (Session Initiation Protocol)
  + SIPVicious
  + Svmap
- RPC (Remote Procedure Call)
  + nmap -sR 192.168.0.1-254

# Vulnerability Analysis
- Classification of Vulnerabilities
  + Misconfiguration
  + Default Installation
  + Buffer Overflows
  + Unpatched Servers
  + Design Flaws
  + Operating Systems Flaws
  + Application Flaws
  + Open Services
  + Default Passwords
- Types of Vulnerability Analysis
  + Identify weaknesses
  + Additional security measures
  + Network vulnerabilities
  + Open ports
  + Running services
  + Application weaknesses
  + Service weaknesses
  + Configuration errors
  + Password weaknesses
- Types of Vulnerability Assessments
  + Active assessments
  + Passive assessments
  + External assessments
  + Internal assessment
  + Host-based assessments
  + Network assessments
  + Application assessments
  + Wireless network assessments
- Tools:
  + OpenVAS
  + Nessus
  + Nexpose
  + MBSA (Microsoft Baseline Security Analyzer)
  + SCAP (Security Content Automation Protocol)
  + Exploit Scanners
- Remediating:
  + Host Vulnerabilities
    + Looking at Servers
    + Looking at Endpoints: Desktops, Laptops, Phones, Tablets, ...
    + Looking at ICS (Industrial Control Systems) & SCADA (Supervisory Control and Data Acquisition)
  + Network Vulnerabilities
    + Keeping up to date with Updates
    + SSL & TLS
    + DNS
    + Internal IP Exposure: NAT
    + VPNs
  + Virtual Environment Vulnerabilities
    + Administration Interface Access
    + Virtual Host Patching
    + Virtual Guest Patching
    + Virtual Network Concerns
    + VM Escape
  
# System Hacking
## The 3 Goals and 5 Phases
- Gaining Access
  + Cracking passwords
  + Escalating privileges
- Maintaining Access
  + Launching apps
  + Hiding your tools
- Covering Your Tracks
  + Messing with the logs
## Phase 1: Gaining Access - Cracking Passwords
## Phase 2: Gaining Access - Escalating Privileges
## Phase 3: Maintaining Access - Executing Applications
## Phase 4: Maintaining Access - Hiding Your Tools
## Phase 5: Covering Your Tracks - Clearing Logs and Evidence

# Malware Threats

# Hacking Web Servers

# Hacking Web Applications

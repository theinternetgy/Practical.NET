## Understanding Ethical Hacking
- Information Security
- Technology Triangle
- Security Threats
- Attack Vectors
- Hacking Concepts
- Hacking Phases
- Attack Types

## Reconnaissance/Footprinting
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

## Scanning Networks
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
  
## Enumeration
- Defaults & NetBIOS (Network Basic Input/Output System)
- SNMP (Simple Network Management Protocol)
- LDAP (Lightweight Directory Access Protocol)
- NTP (Network Time Protocol)
- SMTP (Simple Mail Transfer Protocol)
- DNS (Domain Name System)
- IPSec (Internet Protocol Security)
- VoIP (Voice over Internet Protocol)
- RPC (Remote Procedure Call)

## Vulnerability Analysis
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
  + Network Vulnerabilities
  + Virtual Environment Vulnerabilities
## System Hacking

## Malware Threats

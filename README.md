# Red-Team-Tools-Collection
<p align="center">
  <img src="https://github.com/z4yt0s/Red-Team-Tools-Collection/blob/main/redteam_tools.png" width="350"/>
</p>

# General Purpose
These tools are universal and are not designed specifically for one system or concrete scenario, but rather applicable in diverse enviroments.

## Network

### Network Scanners
- **[nmap](https://github.com/nmap/nmap) - [C & Lua]:** A powerful network scanning tool that discovers devices on a network, identifies services, and detects vulnerabilities.
- **[masscan](https://github.com/robertdavidgraham/masscan) - [C]:** High-speed port scanner capable of scanning large networks with output similar to nmap.
- **[arp-scan](https://github.com/royhills/arp-scan) - [C & Bash]:** Discovers devices in local IPv4 networks using ARP requests.
- **[netdiscover](https://salsa.debian.org/debian/netdiscover) - [C]:** ARP-based network discovery tool designed for identifying hosts in wireless or wired networks.

### Network Protocols Scanners
- **[netexec](https://github.com/Pennyw0rth/NetExec) - [Python]:** Tool for executing commands remotely on machines over various protocols. Useful for managing and automating tasks across multiple systems in a network.
- **[smbmap](https://github.com) - [Python]:** Tool for enumerating SMB, it is particularly useful for identifying sensitive data and performing remote command execution in Windows networks.

## Exploit Search Engines
- **[exploitdb](https://exploit-db.com/) - [Web]:** Web-based database collecting and indexing known exploits, helping security professionals search for vulnerabilities and associated exploits.
- **[searchsploit](https://gitlab.com/kalilinux/packages/exploitdb) - [C, Python & Ruby]:** Command-line tool for searching the Exploit-DB database for public exploits and vulnerabilities.
- **[vulners](https://vulners.com/) - [Web]:** Search engine indexing vulnerabilities from multiple sources, including CVEs and exploit databases, assisting in finding relevant exploits.
- **[getsploit](https://gitlab.com/kalilinux/packages/getsploit) - [Python]:** Python-based tool for fetching exploit information from the Exploit-DB database.
- **[sploitus](https://sploitus.com/) - [Web]:** Web-based platform for searching and downloading exploits from various databases, including Exploit-DB and others.

## Hash Analysis & Cracking Tools
- **[hashid](https://github.com/psypanda/hashID):** Tool for identifying hash types, helping recognize the format of an unknown hash for further analysis or cracking.
- **[john](https://github.com/openwall/john):** Popular password cracking tool that cracks password hashes using techniques such as dictionary attacks and brute-forcing.
- **[hashcat](https://github.com/hashcat/hashcat):** Fast password recovery tool designed to crack hash types using advanced algorithms and optimized techniques.

## Interactive Shells & Remote Access Tools

### Windows
- **[evil-winrm](https://github.com/Hackplayers/evil-winrm) - [Ruby]:**
- **[nishang](https://github.com/samratashok/nishang) - [PowerShell]:** 

# Web

## Web Discovery
- **[wafw00f](https://github.com/EnableSecurity/wafw00f) - [Python]:** Allows one to identify and fingerprint Web Application Firewall (WAF) products protecting a website.
- **[whatweb](https://github.com/urbanadventurer/WhatWeb) - [Ruby]:** Identifies technologies used by websites, such as web servers, CMS platforms, and security tools, during reconnaissance. 

## Web Fuzzers
- **[wfuzz](https://github.com/xmendez/wfuzz) - [Python]:** Web application brute-forcing tool to discover hidden resources, parameters, and potential security flaws by fuzzing HTTP requests.
- **[dirsearch](https://github.com/maurosoria/dirsearch) - [Python]:** Effective tool for scanning web servers to find hidden directories and files, useful for web application security assessments.
- **[gobuster](https://github.com/OJ/gobuster) - [Go]:** Tool for directory and DNS busting using a wordlist to discover hidden paths and subdomains on web servers.
- **[ffuf](https://github.com/ffuf/ffuf) - [Go]:** Fast web fuzzer designed to brute force HTTP-based resources, often used for discovering directories, files, or parameters in web applications.
- **[feroxbuster](https://github.com/epi052/feroxbuster) - [Rust]:** A fast, simple, recursive and interactive content discovery tool written in Rust.



## Exploitation Frameworks
- **[metasploit](https://github.com/rapid7/metasploit-framework) - [Ruby]:** Widely used exploitation framework that helps security professionals identify, exploit, and validate vulnerabilities in systems and networks.
- **[beef](https://github.com/beefproject/beef) - [JavaScript]:** Browser Exploitation Framework used to exploit web browsers, allowing attackers to gain control over the browser and execute attacks.

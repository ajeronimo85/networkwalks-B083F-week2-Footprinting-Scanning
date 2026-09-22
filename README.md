div align="center">

# 🔍 Week 2 - Footprinting, Scanning & Report Writing

**Building an isolated virtual lab for penetration testing and ethical hacking practice**
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ver-Virtualbox%20v7.2-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Kali%20Linux-v2026.2-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Linux-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Network-10.0.0.0%2F24-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-C00000?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Virtualization-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Kali%20Linux-404040?style=flat-square&labelColor=C00000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/NetworkWalks-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Waqas%20Karim%20CCIE-C00000?style=flat-square" />
</p>

# W2-PM1: Footprintng with Multiple Kali Tools

# Task 1: Domain Registration Lookup (whois)
#Standard lookup

whois networkwalks.com


![](1-screenshot-whois.png)

# Task 2: Web Technology Fingerprinting (whatweb)
whatweb identifies CMS platforms, web server daemons, programming languages, and JavaScript libraries.

![](2-screenshot-whatweb.png)

# Task 3: DNS Name Resolution (nslookup)
nslookup queries DNS servers to resolve a domain name to its IP addresses.

nslookup networkwalks.com

![](3-screenshot-nslookup.png)

# Task 4: HTTP Header & Endpoint Inspection (curl -I)
Sends an HTTP HEAD request to inspect response headers without downloading the page body.

curl -I https://networkwalks.com
curl -I https://example.com

![](4-screenshot-curl.png)

# Task 5: Web Application Firewall Detection (wafw00f)
Detects whether a website sits behind a Web Application Firewall (WAF) and identifies the vendor.

wafw00f https://networkwalks.com
wafw00f https://example.com
![](5-screenshot-wafw00f.png)

# Task 6: Full DNS Record Enumeration (dnsrecon)
Automates the retrieval of all DNS record types (SOA, NS, MX, A, AAAA, TXT, SPF) in a single pass.

dnsrecon -d networkwalks.com -t std
![](6-screenshot-dnsrecon.png)

 # W2-PM3: Maltego-based Footprinting Attacks
Workflow: Entity link analysis starting from domain networkwalks.com, executing transforms to discover DNS names, IP blocks, Netblocks, and organizational email addresses.

![](7-screenshot-maltego.png)

# W2-PM4: theHarvester-based Footprinting Attacks
theHarvester -d networkwalks.com -b all -l 100
Harvests public corporate emails, employee names, search engine subdomains, and public IP ranges.

![](8-screenshot-theharvester.png)

# W2-PM5: Zenmap & Nmap Network Scanning (Essential)
![](4-screenshot-android-networksethings.png)




![](4-screenshot-android-networksethings.png)



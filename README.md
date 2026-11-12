
# 🛡️ PENETRATION TESTING

## 🌐 Week 02 – Network Footprinting & Network Scanning

**Organization:** Networkwalks  
**Internship Program:** Cybersecurity Internship  
**Week:** 02  
**Status:** Completed

---

## 📌 About This Project

This repository contains my Week 2 practical tasks completed during my cybersecurity internship at **Networkwalks**.

This week covers two important penetration testing activities:

- **Network Footprinting (W2-PM1):** Gathering publicly available information about the `networkwalks.com` domain using Kali Linux tools and Google Hacking Database (GHDB).
- **Network Scanning (W2-PM5):** Scanning my own local network using Zenmap to identify active hosts and network devices.

---

## 🎯 Project Objectives

- Perform basic network footprinting.
- Collect publicly available domain information.
- Identify website technologies and DNS records.
- Explore Google Hacking Database (GHDB).
- Research webcam-related publicly indexed information.
- Discover live hosts on my own local network.
- Understand security risks and preventive measures.

---

## 🧰 Tools & Technologies Used

| Tool | Purpose |
|---|---|
| Kali Linux | Footprinting and reconnaissance |
| Windows | Network scanning |
| WHOIS | Domain registration information |
| WhatWeb | Website technology detection |
| nslookup | DNS lookup |
| curl -I | HTTP response header analysis |
| WAFW00F | Web Application Firewall detection |
| DNSRecon | DNS record enumeration |
| GHDB | Google-based information discovery |
| Zenmap | Network scanning and host discovery |
| Windows CMD | IP and MAC address identification |

---

## 🌐 Task 01: Network Footprinting (W2-PM1)

**Objective:** Perform footprinting on the `networkwalks.com` domain using Kali Linux tools.

### 🔍 Activities Performed

1. **WHOIS Lookup:** Collected domain registration information, including registration dates and name servers.
2. **WhatWeb Scan:** Identified website technologies, including WordPress and WP Download Manager.
3. **DNS Lookup:** Used nslookup to identify the domain's IP address.
4. **HTTP Header Analysis:** Used curl -I to examine HTTP response headers.
5. **WAF Detection:** Used WAFW00F to identify ModSecurity (SpiderLabs).
6. **DNS Enumeration:** Used DNSRecon to collect DNS, mail, and other service-related records.
7. **Google Hacking Database (GHDB):** Explored webcam-related Google search techniques to understand how publicly indexed camera-related information may be exposed.

### 📸 Practical Evidence

Screenshots of commands and observed results are included in the respective task folders.

---

## 🔍 Task 02: Network Scanning (W2-PM5)

**Objective:** Scan my own local network using Zenmap to identify active hosts and network devices.

### 🖥️ Activities Performed

1. Identified the local IP address using Windows CMD.
2. Checked the MAC address and network configuration.
3. Opened Zenmap on Windows.
4. Scanned my authorized local network.
5. Identified four live hosts in the example network.
6. Observed available host and network information.

### 📸 Practical Evidence

Screenshots of Zenmap scan results and Windows CMD commands are included in the respective task folders.

---

## 📊 Key Findings

| # | Finding | Risk Level |
|---|---|---|
| 1 | Website technology information identified | Medium |
| 2 | Server IP address identified | Low |
| 3 | HTTP technical information exposed | Low |
| 4 | WAF technology identified | Low |
| 5 | DNS infrastructure information collected | Medium |
| 6 | Four live hosts discovered on the local network | Medium |
| 7 | Webcam-related public information researched using GHDB | Medium |

*Note: These are preliminary observations, not confirmed vulnerabilities.*

---

## 💡 Security Recommendations

1. Keep WordPress, plugins, and website software updated.
2. Avoid exposing unnecessary server information.
3. Configure appropriate HTTP security headers.
4. Keep WAF rules updated and properly configured.
5. Review DNS records regularly.
6. Monitor local network devices and remove unauthorized connections.
7. Secure webcam devices with strong passwords, authentication, and updated firmware.

---

## 🎓 Learning Outcomes

Through these practical activities, I gained knowledge of:

- Network Footprinting and Reconnaissance.
- Domain Information Gathering.
- DNS Enumeration.
- Website Technology Detection.
- Google Hacking Database (GHDB).
- Webcam-Related Information Research.
- HTTP Header Analysis.
- Web Application Firewall Detection.
- Local Network Scanning.
- Live Host Discovery.
- Basic Security Assessment.

---

## 📝 Conclusion

This Week 2 internship task improved my understanding of network footprinting and network scanning. I learned how to use different Kali Linux tools to collect publicly available information about a domain. I also explored GHDB for webcam-related information and used Zenmap to identify live devices on my own local network. These activities strengthened my knowledge of reconnaissance, DNS, website technologies, and network discovery. Overall, this experience helped improve my cybersecurity skills and understanding of ethical hacking practices.

---

## ⚠️ Disclaimer

All activities documented in this repository were performed on systems and devices that I own or for which I had proper written authorization.

This repository is intended strictly for educational, training, and research purposes. Unauthorized access or misuse of any information is prohibited.

**Always obtain proper permission before conducting security testing. Ethical hacking starts with authorization.**

---

## 💻 Internship Information

| Detail | Information |
|---|---|
| Organization | Networkwalks |
| Program | Cybersecurity Internship |
| Week | 02 |
| Main Topic | Penetration Testing |
| Task 01 | Network Footprinting (W2-PM1) |
| Task 02 | Network Scanning (W2-PM5) |
| Operating Systems | Kali Linux & Windows |
| Status | Completed |

---

## ⭐ Acknowledgement

Special thanks to **Networkwalks** and the internship instructors for providing this learning opportunity and helping me improve my practical cybersecurity skills.

---

**#CyberSecurity #PenetrationTesting #EthicalHacking #NetworkFootprinting #NetworkScanning #KaliLinux #Zenmap #GHDB #Networkwalks**

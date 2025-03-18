<div align="center" style="background-color:#1e1e2e; color:#ffffff; padding:20px; border-radius:10px;"> <H2>Abraham's Cybersecurity Portfolio</H2><p><H4>abfembest@gmail.com</H4></p>
</div>
<div align="center" style="background-color:#1e1e2e; color:#ffffff; padding:20px; border-radius:10px;">

## 🚀 Tools & Technologies Capabilities 

### 🖥️ **Networking & Security Tools**  
🛜 **Cisco Devices:** Routers, Switches, Console Cable  
📟 **CLI Tools:** Cisco IOS, Putty  
🦈 **Traffic Analysis:** Wireshark, Nmap  

### 🛡️ **Cybersecurity & Penetration Testing**  
🐧 **Linux Distros:** Kali Linux, Ubuntu  
🔍 **Vulnerability Scanners:** Nessus, OpenVAS  
🕵️‍♂️ **Penetration Testing:** Metasploit, Burp Suite, John the Ripper  
🛠 **SIEM & Monitoring:** Splunk, ELK Stack  

### 🏗️ **Programming & Scripting**  
🐍 **Languages:** Python, Bash  
💻 **Automation & Scripting:** PowerShell, Ansible  

</div>

 <H2 align="center" style="background-color:#1e1e2e; color:#ffffff; padding:20px; border-radius:10px;">IMPLEMENTING IP ROUTING ON NETWORK ROUTER.</H2>
<h5>Topology</h5>
 <img src="https://github.com/user-attachments/assets/23b97df1-c44b-4201-96e9-24195638a2c6" width="70%">
 
 - **Addressing Table**
 <p><img src="https://github.com/user-attachments/assets/426d7a35-8a2f-4f28-b65f-e270ba82dcdb" width="70%"> </p>
 
### 🔹 Task  
Configure IP addressing, interface settings, and static routing on network devices to establish connectivity between subnets.

### 🔧 Action  
- I assigned **IP 10.1.1.2/30** to the router's **s0/0/0** interface and set **clock rate to 128000**.  
- I activated the interface with `no shutdown`.  
- I configured **recursive static routing** on R1 to **192.168.1.0/24** via **10.1.1.2**.  
- I set a **directly connected static route** on R3 to **192.168.0.0/24** via **s0/0/0**.  
- I removed static routes from R1 using `no ip route`.  
- I added a **default route on R1** to **0.0.0.0/0** via **s0/0/1**.

### 📈 Results  
✅ I established successful communication between networks.  
✅ I ensured efficient static route configuration and failover.  
✅ I simplified the routing table with a default route for external traffic.
<hr>


<H2 align="center" style="background-color:#1e1e2e; color:#ffffff; padding:20px; border-radius:10px;">IMPLEMENTING ACCESS SECURITY AND PASSWORD COMPLEXITY ON EDGE ROUTER.</H2>
 <h5>Topology</h5>
 <img src="https://github.com/user-attachments/assets/03c92f4c-0db3-44f6-948f-2bf264933d0b" width="70%">
 
![image](https://github.com/user-attachments/assets/c28225b0-a267-433f-a5ed-916a6de449a9)

### 🔹 Task  
To configure secure access control and enforce password complexity to enhance edge router security.


<img src="https://github.com/user-attachments/assets/c28225b0-a267-433f-a5ed-916a6de449a9" width="70%">

### 🔧 Action  
 - I enforced strong passwords with user privilege levels
 - I enabled password encryption to prevent plain-text exposure
 - I implemented login security to block failed attempts

### 📈 Results  
✅ I improved access security with AAA authentication and privilege control.
✅ I prevented unauthorized access through password encryption and complexity enforcement.
✅ I secured remote management by replacing Telnet with SSH.
  <hr>


<H2 align="center" style="background-color:#1e1e2e; color:#ffffff; padding:20px; border-radius:10px;">IMPLEMENTING ACCESS CONTROL LISTs (ACLs)SECURITY.</H2>
<h5>Topology</h5>

 <img src="https://github.com/user-attachments/assets/b8f97cc1-6ce6-4916-999f-2a6bd897c71d" width="70%">

	
## 📌 Task  
The task was to enhance network security by **implementing Access Control Lists (ACLs)** to regulate traffic flow and restrict unauthorized access.  

## 🔧 Action  
- **I configured standard and extended ACLs** to filter traffic based on IP, protocols, and ports.  
- **I applied ACL rules** to router interfaces to permit or deny specific traffic.  
- **I logged and monitored traffic patterns** to refine security policies.
<img src="https://github.com/user-attachments/assets/f19380a2-3f79-4ef0-88d5-d400f37932d0" width="70%">
 <img src="https://github.com/user-attachments/assets/1b39f5aa-fe72-48de-a18b-bbaec66067c8" width="70%">

## 📈 Result  
✅ **I Restricted unauthorized access**, reducing security risks.  
✅ **I improved network performance** by filtering unnecessary traffic.  
✅ **I enhanced monitoring** with logged access attempts for auditing. 

  <hr>
  
  <H2> -Implementing Zone-Based Policy Firewall (ZBF) Security</H2>  

## 📌 Task  
Enhance network security by **configuring a Zone-Based Policy Firewall (ZBF)** to control traffic between security zones and protect critical resources.  

## 🔧 Action. 
- **I created security zones** (e.g., Inside, Outside, DMZ) and assigned interfaces accordingly.  
- **I Defined class maps** to identify traffic types and created policy maps to enforce security rules.  
- **I applied zone-pair policies** to regulate traffic flow between security zones.
  
<img src ="https://github.com/user-attachments/assets/b37af828-fd00-440e-8580-b8da3c29c421" width = "70%">


## 📈 Result  
✅ **Segmented network traffic**, reducing the attack surface and improving security.  
✅ **Blocked unauthorized access**, ensuring only permitted traffic flows between zones.  
✅ **Enhanced visibility and control**, optimizing firewall policies for better threat mitigation.  
<hr>




<H2>🛡️ Implementing Intrusion Detection & Prevention (IDS/IPS) Security  </H2>
## 📌 Task  
Strengthen network security by **deploying Intrusion Detection Systems (IDS) and Intrusion Prevention Systems (IPS)** to monitor, detect, and mitigate threats in real-time.  

<img src = "https://github.com/user-attachments/assets/c9d028e8-d9ea-4c6d-8135-3890d1f16dba" width = "80%">

## 🔧 Action  
- **I configured IDS tools** to analyze network traffic for suspicious activity.  
- **I deployed IPS solutions** to actively block threats.  
- **I set up logging and alerts** to detect and respond to anomalies efficiently.


<img src = "https://github.com/user-attachments/assets/10099ae1-c8ce-4735-a1b5-eddaa1c0a71d" width = "80%">

## 📈 Result  
✅ **Enhanced threat detection**, identifying and mitigating cyber threats in real-time.  
✅ **Reduced security breaches** by proactively blocking malicious traffic.  
✅ **Improved incident response** with automated alerts and forensic logging.  



 <H2 align="center" style="background-color:#1e1e2e; color:#ffffff; padding:20px; border-radius:10px;">Securing the Local Area Network.</H2>
<h5>Topology</h5>
 <img src="https://github.com/user-attachments/assets/f791b202-1d86-444b-ace8-c994ee7c4833" width="70%">




## 📌 Task  
To prevent unauthorized access and mitigate security risks local area network 
## 🔧 Action  
- **I configured port security** on switch interfaces to allow only specific MAC addresses.  
- **I set violation modes** to protect, restrict, or shut down ports upon unauthorized access.  
- **I Monitored and logged security violations** for auditing and incident response.

<h4>Implementatation</h4>
 <p><img src="https://github.com/user-attachments/assets/e4f5369f-8404-4409-b0f7-53d2fc02cf17" width="70%"></p>


## 📈 Result  
✅ **Prevented unauthorized device access**, enhancing LAN security.  
✅ **Reduced risk of MAC address spoofing and network attacks**.  
✅ **Improved network stability** by limiting dynamic address learning.  


<H2 align="center" style="background-color:#1e1e2e; color:#ffffff; padding:20px; border-radius:10px;">Cryptographic Security Using Encryption & Hashing.</H2>


## 📌 Task  
To ensure **data confidentiality, integrity, and authenticity** 
## 🔧 Action  
- **I applied encryption algorithms** (AES, RSA) to secure data in transit and at rest.  
- **I implemented hashing functions** (SHA-256, MD5) to verify data integrity.  
- **I configured secure key management** to enhance cryptographic security.
- 
<h5>Implementation</h5>

<img src="https://github.com/user-attachments/assets/ce38d474-cb4e-4094-addf-794f95c85194" width="70%">


## 📈 Result  
✅ **Ensured secure communication** by encrypting sensitive data.  
✅ **Prevented unauthorized modifications** with hash-based integrity checks.  
✅ **Strengthened authentication** by securing password storage.  


<H2 align="center" style="background-color:#1e1e2e; color:#ffffff; padding:20px; border-radius:10px;">🛡️ Securing Network Communication with VPN & IP Security</H2>

![image](https://github.com/user-attachments/assets/b2103eba-f4fb-4960-ace2-3a88564093a6)

# 🛡️ Securing Network Communication with VPN & IP Security  

## 📌 Task  
Enhance **network security and privacy** by implementing **VPN (Virtual Private Network) and IP security (IPsec)**.

## 🔧 Action  
- **Configured VPN tunnels** (IPsec, SSL) to encrypt remote access connections.  
- **Implemented IPsec protocols** (AH, ESP) to secure IP communication.  
- **Deployed authentication and encryption policies** to ensure secure data exchange.  

## 📈 Result  
✅ **Established secure remote access**, protecting sensitive data from interception.  
✅ **Ensured end-to-end encryption**, preventing unauthorized access.  
✅ **Enhanced network reliability and confidentiality** for secure communication.  



 ###-Implementing IP routing on Network Router.
  - [Firewall Technology Implementations!](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [IDS/IPS Implementations](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [LAN Security](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Cryptographics Implementation](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [VPN/IPSecs](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [ASA firewall Configuration](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Computer Network / Security Overview!](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [and more....](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
 [ +++++++++++++++++++++++++++++++++]
- <b><h3>Penetration Testing</h3></b>
  - [Linux Command, Administrative (AAA)](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Footprinting and Reconnaissance](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Hacker Test, Enumerating SMB](https://github.com/abfembest/cybersecurity/assets/59797153/52fde834-8e7c-48cc-b6eb-eea575c5f0e1)
  - [Social Engineering Attacks with Social Engineering Toolkit](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Client Side Exploitations using BeEF application](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Malware Threats](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Implementing ACLs and Firewalking (Vulnerability Discovery)](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Antivirus evasion, Creating Malicious Payloads Using the Veil Framework](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Implementing Session Hijacking, Packet Crafting with Scapy](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Capturing web username and passwords, OpenSUSE, Pfense](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Computer Network / Security Overview!](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Pentest XSS, SQL Ingestion, URL Encoding](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Web Pentesting with Nikto & OWSP Zap](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Creating and Installing SSL Certificates](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Wireless, Wireshark, NMAP, TCPDUMP, Burpsuites, and lot more](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
   - [and more....](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
     [++++++++++++++++++++++++++]
     - <b><h3>Application Security Projects</h3></b>
  - [Top 10 OWASP vulnerabilities](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Hacking Hidding Score board](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Hacking, Preventing confidential Documents](https://github.com/abfembest/cybersecurity/assets/59797153/52fde834-8e7c-48cc-b6eb-eea575c5f0e1)
  - [Hacking other users' details](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Exposed metrics, Error message vulnerabilities](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Error handling, Privacy Policies](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [DOM XSS, SQL Ingestion, AAA (Vulnerability Discovery)](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Password harvesting, Pass the hash ](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Implementing Session Hijacking, Packet Crafting with Scapy](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Capturing web username and passwords, OpenSUSE, Pfense](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Computer Network / Security Overview!](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Pentest XSS, SQL Ingestion, URL Encoding](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Web Pentesting with Nikto & OWSP Zap](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Creating and Installing SSL Certificates](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
  - [Wireless, Wireshark, NMAP, TCPDUMP, Burpsuites, and lot more](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
   - [and more....](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
   - [and more....](https://github.com/abfembest/cybersecurity/assets/59797153/e3156ad9-9a87-403a-b30a-6f83666bdba9)
     [++++++++++++++++++++++++++]
- <b>PowerShell</b>
  - [Windows EventLog: Failed RDP Logins Source IP to full GeoData Conversion](https://github.com/joshmadakor1/Sentinel-Lab)
  - [JWipe (Disk Wiping Utility)](https://github.com/joshmadakor1/Jwipe.PowerShell)
  - [Active Directory Bulk User Creation](https://github.com/joshmadakor1/AD_PS)
  - [FIM (File Integrity Monitor)](https://github.com/joshmadakor1/PowerShell-Integrity-FIM)
- <b>C# (.NET Desktop Applications)</b>
  - [Ransomware Proof of Concept (Encrypter)](https://github.com/joshmadakor1/EncrypterPOC)
  - [Ransomware Proof of Concept (Decrypter)](https://github.com/joshmadakor1/DecrypterPOC)
  - [Keylogger with Email Capability](https://github.com/joshmadakor1/Key-Logger-With-Email)
- <b>Python</b>
  - [Package Delivery Application (Data Structures and Algorithms Demo)](https://github.com/joshmadakor1/Package-Delivery-Pathfinding-Algorithm)

<h2>📺 Popular YouTube Videos</h2>

- [How to get into Cybersecurity Starting From Zero](https://www.youtube.com/watch?v=a83ASGn_V_s)
- [A Day in the Life of a Cybersecurity Anayst](https://www.youtube.com/watch?v=uHy3oM7NnoU)
- [How to Create a KeyLogger (C#)](https://www.youtube.com/watch?v=N-L9hklSlNk)
- [Ransomware Demonstration (C#)](https://www.youtube.com/watch?v=OfvdQeh79s0)
- [Is WGU Legit?](https://www.youtube.com/watch?v=E2MwRWxDBkA)

<h2> 🤳 Connect with me:</h2>

[<img align="left" alt="JoshMadakor | YouTube" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/youtube.svg" />][youtube]
[<img align="left" alt="JoshMadakor | Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />][twitter]
[<img align="left" alt="JoshMadakor | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="JoshMadakor | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />][instagram]

[twitter]: https://twitter.com/joshmadakor
[youtube]: https://www.youtube.com/c/joshmadakor
[instagram]: https://www.instagram.com/joshmadakor/
[linkedin]: https://linkedin.com/in/joshmadakor

<!--
**joshmadakor1/joshmadakor1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

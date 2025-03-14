 # Cybersecurity Projects
### 🛠 Tools Used  
- **Putty, Console cable, Cisco router, switches** 
- **CLI Commands** (Cisco IOS)  
- **Cisco IOS CLI** (AAA Configuration)
- **Wireshark** (Packet Capture & Analysis) 
- **LINUX, Kali, Python, NMAP, SIEMs, Burp Suite, Metasploit, Nessus, Wireshark, John the Ripper, etc.**
  
 ### 1. IMPLEMENTING IP ROUTING ON NETWORK ROUTER.
 - **Topology**
 <img src="https://github.com/user-attachments/assets/23b97df1-c44b-4201-96e9-24195638a2c6" width="500">
 
 - **Addressing Table**
 <p><img src="https://github.com/user-attachments/assets/426d7a35-8a2f-4f28-b65f-e270ba82dcdb" width="500"> </p>
 
### 🔹 Task  
To configure IP addressing, interface settings, and static routing on network devices to establish connectivity between subnets.

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
✅ I simplified routing table with a default route for external traffic.
  <hr>


 ### 3. IMPLEMENTING ACCESS SECURITY AND PASSWORD COMPLEXITY ON EDGE ROUTER.
 - **TOPOLOGY**
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


### 4. IMPLEMENTING ACCESS CONTROL LISTs (ACLs)SECURITY.
 - **TOPOLOGY**

 <img src="https://github.com/user-attachments/assets/b8f97cc1-6ce6-4916-999f-2a6bd897c71d" width="70%">
	
## 📌 Task  
The task was to enhance network security by **implementing Access Control Lists (ACLs)** to regulate traffic flow and restrict unauthorized access.  

## 🔧 Action  
- **I configured standard and extended ACLs** to filter traffic based on IP, protocols, and ports.  
- **I applied ACL rules** to router interfaces to permit or deny specific traffic.  
- **I logged and monitored traffic patterns** to refine security policies.

 <img src="https://github.com/user-attachments/assets/1b39f5aa-fe72-48de-a18b-bbaec66067c8" width="70%">

## 📈 Result  
✅ **I Restricted unauthorized access**, reducing security risks.  
✅ **I improved network performance** by filtering unnecessary traffic.  
✅ **I enhanced monitoring** with logged access attempts for auditing. 


  <hr>


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

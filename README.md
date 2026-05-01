# Telnet Traffic Analysis with Wireshark

## Overview
This project demonstrates the security risks of using Telnet by capturing and analyzing unencrypted network traffic in a controlled virtual lab environment. Using Wireshark, network packets were inspected to reveal sensitive information transmitted in plaintext.

---

## Lab Environment
The experiment was conducted using two virtual machines:

- **Client:** Windows 11  
  - Wireshark  
  - PuTTY  

- **Server:** Ubuntu  
  - Telnet service enabled  

- **Network:** Private virtual network between the two VMs  

---

## Tools & Technologies
- Wireshark (Packet Analysis)  
- PuTTY (Remote Connection Client)  
- Telnet (Insecure Protocol)  
- Ubuntu (Linux Server)  
- Windows 11 (Client OS)  

---

## Methodology
1. Started packet capture using Wireshark on the Windows 11 VM  
2. Initiated a Telnet connection from Windows to the Ubuntu server using PuTTY  
3. Logged into the Ubuntu system via Telnet  
4. Captured and monitored network traffic during the session  
5. Filtered and analyzed packets within Wireshark  

---

## Key Findings
- Telnet transmits all data in **plaintext**  
- User credentials (username and password) were visible in captured packets  
- No encryption is used, making the protocol highly insecure  
- Attackers can easily intercept sensitive information using packet sniffing tools  

---

## Screenshots
*(Add screenshots here)*  
Examples:
- Wireshark packet capture  
- Telnet login session via PuTTY  
- Packet showing plaintext credentials  

---

## Security Implications
This project highlights why Telnet is considered obsolete and insecure. The lack of encryption makes it vulnerable to eavesdropping and man-in-the-middle attacks.

---

## ✅ Conclusion
The experiment confirms that Telnet should not be used in modern systems. Secure alternatives such as SSH should be implemented to protect sensitive communications.

---

## 🔒 Disclaimer
This project was conducted in a controlled virtual lab environment using private IP addresses.  
No real user data, production systems, or external networks were involved.

---

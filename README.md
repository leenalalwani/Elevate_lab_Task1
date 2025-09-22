# Elevate_lab_Task1
# 🔍 Cybersecurity Internship – Task 1  
**Topic:** Local Network Port Scanning & Analysis  

---

##  Objective  
Learn to discover open ports on devices in the local network to understand network exposure and potential security risks.

---

## Tools Used  
- **Nmap** – for network scanning, host discovery, and port enumeration.  
- **Wireshark** *(optional)* – for capturing and analyzing network packets in real time.

###  Install Nmap  
- Downloaded and installed Nmap from [https://nmap.org/download.html](https://nmap.org/download.html).  
- Verified installation using:  
```bash
nmap --version
### Summary

--Performed network reconnaissance on my local network to understand potential exposure.

Used Nmap to scan the local IP and successfully identified four open ports:

22/tcp – SSH

80/tcp – HTTP

3000/tcp – PPP

7777/tcp – CBT

Learned the services running on each port and their potential security implications.

Optionally used Wireshark to capture and analyze real-time network traffic, observing how devices communicate on the network.

Gained hands-on experience in:

Discovering active hosts and open ports on a network

Understanding potential attack surfaces created by open ports

Observing packet flow and network behavior

Improved knowledge of network security best practices, including:

Closing unnecessary ports

Using firewalls effectively

Regular monitoring of network activity to reduce risk

Overall, this task provided practical exposure to cybersecurity tools and techniques, strengthening skills needed for network auditing and protection.

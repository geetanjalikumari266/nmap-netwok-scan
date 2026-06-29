#Task 1: Scan Your Local Network for Open Ports

Objective
To discover open ports on devices in the local network and understand network exposure.

Tools Used
Nmap 7.95
Kali Linux
Wireshark (Optional)

Procedure
Verified Nmap installation.
Identified local network range.
Performed TCP SYN scan using Nmap.
Identified open ports and services.
Analyzed potential security risks.

Commands Used
nmap --version
sudo nmap -sS 192.168.1.0/24
sudo nmap -sV 192.168.1.1

Scan Results
Port	Service
22	SSH
23	Telnet
53	DNS
80	HTTP
1900	UPnP

Security Risks
SSH may be vulnerable to brute-force attacks if weak passwords are used.
Telnet transmits data in plaintext and is considered insecure.
DNS services can be abused if misconfigured.
HTTP traffic is not encrypted.
UPnP may expose devices to unauthorized access.

Result
The scan successfully identified open ports and services running on the target device.

Conclusion
Nmap helped identify exposed services on the local network and highlighted potential security risks associated with open ports.

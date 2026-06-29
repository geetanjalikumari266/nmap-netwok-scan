# Task 1: Scan Your Local Network for Open Ports

## Objective
To discover open ports on devices in the local network and understand network exposure.

## Tools Used
- Nmap 7.95
- Kali Linux
- Wireshark (Optional)

## Procedure
1. Verified Nmap installation.
2. Identified local network range.
3. Performed TCP SYN scan.
4. Identified open ports and services.
5. Analyzed security risks.
## Commands Used

### Check Nmap Version

```bash
nmap --version
```

### Find Local IP Address

```bash
hostname -I
```

### Perform TCP SYN Scan

```bash
sudo nmap -sS 192.168.1.17/24
```

### Save Scan Results

```bash
sudo nmap -sV 192.168.17.24 -oN scan_results.txt
```
## Scan Results

| Port | Service |
|------|---------|
| 22 | SSH |
| 23 | Telnet |
| 53 | DNS |
| 80 | HTTP |
| 1900 | UPnP |

## Conclusion

The scan successfully identified open ports and services running on the target device.
Result
The scan successfully identified open ports and services running on the target device.

Conclusion
Nmap helped identify exposed services on the local network and highlighted potential security risks associated with open ports.

## Screenshot

![image alt](https://github.com/geetanjalikumari266/nmap-netwok-scan/blob/61c95d315dd42e5ab06e9b5142fc197ed836f9e4/IMG-20260629-WA0011.jpg)

![image alt](https://github.com/geetanjalikumari266/nmap-netwok-scan/blob/1c95439c0baa635ff7523f59fdf51ad6e6844101/IMG-20260629-WA0009.jpg)

![image alt](https://github.com/geetanjalikumari266/nmap-netwok-scan/blob/cd117e61b22f9a94ca3fd38e436f505568f983bd/IMG-20260629-WA0010.jpg)

# ElevateLabsInternship
# Task 1: Scan Your Local Network for Open Ports

## 🛠 Tools Used
- Nmap

## 🔍 Objective
To discover open ports in the local network using TCP SYN scan and understand the exposure of services.

## 🧪 Steps Followed
1. Installed Nmap on Kali Linux.
2. Identified local IP range: `192.168.1.0/24`.
3. Ran TCP SYN scan using: `nmap -sS 192.168.1.0/24`.
4. Documented active hosts and open ports.
5. Researched services and identified potential risks.
6. Saved scan output in `scan_result.txt`.

## 📁 Files Included
- `scan_result.txt` – Raw Nmap output
- `screenshots/` – Visual proof of scan
- `report.md` – Risk analysis & summary (optional)

## 🧠 Key Learnings
- Importance of network reconnaissance
- Security risks from open ports like Telnet, SMB, MySQL
- How to interpret port scan results

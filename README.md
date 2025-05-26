# Nmap Local Network Scan

## Overview
This project demonstrates how to scan a local network (`10.0.2.0/24`) for open ports using Nmap. The goal is to identify potential security risks from exposed services.

## Tools Used
- **Nmap** - Network scanning tool
- **Linux command line**

## Files Included
- 'scan_results.txt' - Raw output from Nmap scan
- Screenshots

## How to Reproduce

1.Run the Nmap Scan using the command
  sudo nmap -sS 10.0.2.0/24

  Flags:
  -sS: SYN scan (doesn’t complete TCP handshake, less detectable).
  10.0.2.0/24: Scans all IPs from 10.0.2.1 to 10.0.2.254

2. Save Results
   sudo nmap -sS 10.0.2.0/24 -oN scan_results.txt

3. Your scan is completed with the data saved in to text file.

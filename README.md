 Task 1 – Network Reconnaissance using Nmap

This repository contains my submission for *Task 1* of the Cybersecurity Internship.  
In this task, I explored how to scan a local network using NMAP to identify active devices and open ports, helping me understand the basics of *network exposure* and *reconnaissance techniques*.



##  Objective

To perform a TCP SYN scan on my local network using NMAP, analyze the scan results, identify potential security risks, and document findings.



##  Tools Used

- Nmap
- Local mobile hotspot network
- netstat -nr (to find gateway IP)



##  Methodology

1. Used netstat -nr to find my gateway IP (***.***.**.*)
2. Determined local subnet: ***.***.**.*/24
3. Ran an Nmap TCP SYN scan:
   ```bash

   nmap -sS 192.168.138.82/24

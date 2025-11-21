# Standard Scanning

1. Start up your Kali Linux VM

2. Then perform an ARP scan by typing in the following command: "arp-scan 192.168.1.0/24". We are able to see the hosts that are on this network. Except for the Kali Linux VM. 

<img width="953" height="741" alt="image" src="https://github.com/user-attachments/assets/16ca6af5-2026-4e72-b6a7-223275c9df9d" />

Result of Step 2

3. Next type in the following command to generate a TCP scan of 192.168.10 and determine which ports are open: "nmap -sT 192.168.1.10".

<img width="932" height="513" alt="image" src="https://github.com/user-attachments/assets/c44d19a0-8666-4f25-81cc-1c27b5a089ca" />

Result of Step 3


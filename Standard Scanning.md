# Standard Scanning

1. Start up your Kali Linux VM

2. Then perform an ARP scan by typing in the following command: "arp-scan 192.168.1.0/24". We are able to see the hosts that are on this network. Except for the Kali Linux VM. 

<img width="953" height="741" alt="image" src="https://github.com/user-attachments/assets/16ca6af5-2026-4e72-b6a7-223275c9df9d" />

Result of Step 2

3. Next type in the following command to generate a TCP scan of 192.168.10 and determine which ports are open: "nmap -sT 192.168.1.10".

<img width="932" height="513" alt="image" src="https://github.com/user-attachments/assets/c44d19a0-8666-4f25-81cc-1c27b5a089ca" />

Result of Step 3

4. Now do the same step as step 4 but do it for 192.168.1.20.

<img width="934" height="557" alt="image" src="https://github.com/user-attachments/assets/de5a9a1f-aaa9-45ac-b6e8-349b7308b6c3" />

Result of Step 4

5. Now do the same step as step 4 but do it for 192.168.1.30.

<img width="948" height="644" alt="image" src="https://github.com/user-attachments/assets/7a26c90c-bfdb-4c69-89ca-a8e2925a4054" />

Result of Step 5

6. Now do the same step as step 4 but do it for 192.168.1.254.

<img width="935" height="360" alt="image" src="https://github.com/user-attachments/assets/0b0a52d9-3aee-427f-9a45-23fd2128a64f" />

Result of Step 6

7. Now we will do an OS scan to determine the operating system of this host. To do this type in the command: "nmap -O 192.168.1.10 | tail". 

<img width="929" height="526" alt="image" src="https://github.com/user-attachments/assets/645ef506-1f40-4e0c-a7c1-4e4fa515061e" />

Result of Step 7

8. Do the same step as step 7 but do it for 192.168.1.20.

<img width="940" height="655" alt="image" src="https://github.com/user-attachments/assets/15267342-1545-4afe-9c88-29301926aa50" />

Result of Step 8

9. Do the same step as step 7 but do it for 192.168.1.30.

<img width="940" height="324" alt="image" src="https://github.com/user-attachments/assets/e3da83c4-cd44-4e50-9ddc-f0268d91c07f" />

Result of Step 9

10. Do the same step as step 7 but do it for 192.168.1.254.

<img width="943" height="360" alt="image" src="https://github.com/user-attachments/assets/1bbc8f1e-a201-4294-abb9-1520fa34a88f" />

Result of Step 10

11. Type in the following command to open Zenmap: "Zenmap".

<img width="772" height="723" alt="image" src="https://github.com/user-attachments/assets/2a595dd2-c989-4cae-aa3f-6e8f4ab200cc" />

Result of Step 11

12. Type in the following command in the target field: "192.168.1.*" and click scan to perform an intense scan. *Note this is subject to take up to 5 minutes to complete. 

<img width="797" height="821" alt="image" src="https://github.com/user-attachments/assets/9c29a1dd-0ec2-499a-9455-675fa1f6bb0a" />

<img width="748" height="806" alt="image" src="https://github.com/user-attachments/assets/04558fb9-ee9f-43fe-92c1-12393be0ae70" />

Results of Step 12

13. Click the Ports/Hosts tab to view the open ports and see the banner messages displayed.

<img width="795" height="811" alt="image" src="https://github.com/user-attachments/assets/ee33c9ff-69f3-45c1-86c2-b114276c3702" />

Result of Step 13
